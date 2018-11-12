chapter 7: Making Decisions
==============================

이 장에서는 다음을 배우게 된다.

.. sourcecode:: pycon

    ▶ Using the if statement to make simple decisions
    ▶ Performing more advanced decision making with the if...else statement
    ▶ Creating multiple decision levels by nesting statements


인간은 자연적으로 판단을 하게 되지만 컴퓨터는 매번 판단을 하기 위하여 다음의 임무를 수행한다.

.. sourcecode:: pycon

    1. Obtain the actual or current value of something.
    2. Compare the actual or current value to a desired value.
    3. Perform an action that corresponds to the desired outcome of the
    comparison.




7.1 Making Simple Decisions Using the if Statement
---------------------------------------------------

다음을 출력해 보자.

.. code-block:: python

    TestMe = 6
    if TestMe == 6:
       print("TestMe does equal 6!")


.. code-block:: python


    TestMe = 6
    if TestMe == 6:
       print("TestMe does equal 6!")
       print("All done!")

다음 코드는 입력된 값에 따라 해당 값을 프린트 하는 조건문이다.

.. code-block:: python

    Value = int(input("Type a number between 1 and 10: "))

    if (Value > 0) and (Value <= 10):
       print("You typed: ", Value)



7.2 Choosing Alternatives Using the if...else Statement
---------------------------------------------------------




7.3 Using Nested Decision Statements
----------------------------------------


