# Getting Started

In this exercise we will build a solution diagram based on a real example. For our exercise the focus is on how to build the solution diagram. If you are interested in the details about what is shown in detail we recommend the session XP262.

In the end the solution diagram we are building in this exercise should look similar to this:
<br>![](/exercises/ex0/images/Ex00_01.png)
To allow you to build the solution diagrams more easily we have prepared for you several libraries that should be importet into draw.io before started the exercises.
Furthermore we recommend at least skimming the guidelines to get a better understanding on how to build compliant and consistent solution diagrams.

## Preparing draw.io

1.	Open draw.io - for this exercise we will use the Web client (http://draw.io).
If you haven't used draw.io before the screen might look like this:
<br>![](/exercises/ex0/images/Ex00_02.png)
2. Click on "Create New Diagram". A new window should open:
<br>![](/exercises/ex0/images/Ex00_03.png)
3.Choose "Blank Diagram" from the offered list and give your diagram a name that works for you (in our case "TechEd2023_TaskCenter_Example.drawio). Click on "Create".
4.Note: Depending on the storage you are using different windows might open. We chose to store our diagrams on our local device. In this case a file dialog opens in which we have to decide where we want to store our diagram and what the local filename should be.
If you haven't chosen a default storage yet you might encounter the following window during the process:
<br>![](/exercises/ex0/images/Ex00_04.png)
Feel free to choose whatever storage works best for you
5.Import the "Sneak Preview" libraries for SAP TechEd 2023.
To do so you first need to download the libraries provided here:
<br>[SAP_Arrows_TechEd2023](/exercises/ex0/libraries/SAP_Arrows_TechEd2023.drawio)


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
