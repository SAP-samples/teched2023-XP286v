# Getting Started

In this exercise we will build a solution diagram based on a real example. For our exercise the focus is on how to build the solution diagram. If you are interested in the details about what is shown in detail we recommend the session XP262.

In the end the solution diagram we are building in this exercise should look similar to this:
<br>![](/exercises/ex0/images/Ex00_01.png)

To allow you to build the solution diagrams more easily we have prepared for you several libraries that should be importet into draw.io before started the exercises.

Furthermore we recommend at least skimming the guidelines to get a better understanding on how to build compliant and consistent solution diagrams.

## Preparing draw.io

1.	Open draw.io - for this exercise we will use the Web client (http://draw.io).
<br>![](/exercises/ex0/images/Ex00_03.png)

2.	Import SAP_Service_Icons_TechEd2023.drawio
<br>![](/exercises/ex0/images/Ex00_03.png)

2.	Insert this code.
``` abap
 DATA(params) = request->get_form_fields(  ).
 READ TABLE params REFERENCE INTO DATA(param) WITH KEY name = 'cmd'.
  IF sy-subrc <> 0.
    response->set_status( i_code = 400
                     i_reason = 'Bad request').
    RETURN.
  ENDIF.
```

## Summary

Now that you have ... 
Continue to - [Exercise 1 - Exercise 1 Description](../ex1/README.md)
