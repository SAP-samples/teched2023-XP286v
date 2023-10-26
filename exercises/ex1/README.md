![image](https://github.com/SAP-samples/teched2023-XP286v/assets/28632972/af5d89d3-355f-4387-ab8d-8e4c982f3ca9)# Exercise 1 - Building a Solution Diagram

As mentioned before we will build a solution diagram build on a real example as shown in XP262. For this exercise however we will focus on how to use the iconography and guidelines in the correct way to create a compliant and consistent solution diagram.  
After preparing draw.io it should now be simple for us to build a solution diagram that adheres to the guidlines and uses the latest service icons. Please note that the generic icons for this exercise are not using the new design yet.

The flow of creating a solution diagram in this exercise looks like this:
1. Adding shapes and boxes
2. Adding icons
3. Adding connections
4. Adding names

This is obviously not the only way to do it. Please feel free to use create your own flow.

As a reminder and a template for the exercise, this is the solution diagram we are trying to build:
<br>![](/exercises/ex1/images/Ex01_01.png)

## Exercise 1.1 - Creating Basic Layers and Shapes

1. The first step of the process is always to decide how many layers are needed. As you can see from the template above we need two layers. According to the guidlines "When nesting different areas inside each other alternate between using a fill and not using a fill to provide sufficient contrast between the areas". This said we start by picking a basic shape from the left pane. More specifically "default_L0_filled".
2. As the "innermost area should have no fill as usually this part contains the most icons and text" we now add another basic shape "default_L1_empty".
3. For the application clients we now choose a Shape from the "General" section. A rounded box. In the right pane we can define the look of the box. We choose a light gray filling and a dashed line. Note that you can find the specific color codes in the guidlines.
4. The diagram should now look similar to this:
5. The last think missing in this step of the exercise is now the box for "SAP S/4HANA Cloud". Here we can use another basic shape ("default_L1_empty") and add it to the diagram.
   
## Exercise 1.2 - Adding Icons

1. In the next step we just add the icons to the diagram.
2. Start with the generic icons and put them roughly where you want them to be in the final diagram.
3. Repeat step 2 for the service icons. Note: If you are looking for specific icons and are overwhelmed by the number of service icons, keep in mind that they are sorted alphabetically. Names can be displayed using the mouse over function. This makes finding the specific icons easier.
4. The diagram should now look like this:

## Exercise 1.3 - Adding Connections

1. Now let us add the connections to the diagram. While it would be possible to connect the icons simply using the build in functionality of draw.io, we will take a different approach here and use the arrows provided by SAP. Starting with the "default_single_solid" from the arrows section in the left pane. Use this arrow to build all straight connections. Note that you can connect the arrows to docking point of each element including icons.
2. The diagram should now look similar to this:
3. Now add all connections with one or more elbows by choosing the "default_elbow" element from the arrows section. Note that you can move the points on the connections according to your needs.
4. The diagram should now look similar to this:
5. Finally we add the special connections. In our example the Trust connections. To add them we choose "default_double_solid" from the arrows section. We now create the two Trust connections:
6. Now add two "Annotation_accent3" to the diagram. By selecting the arrow part of the three part element you can now pick the color (R:204/G:1/B:220). Keep that color in mind. From the "Annotation_accent3" element remove the two arrow elements so that just the label is remaining. Add the two labels to the connections we created in the step before.
7. Now click on the connections and change the color to R:204 / G:1 / B:220. The diagram should look like this:
8. After a double click on the labels you can now rename them to "Trust".

## Exercise 1.2 - Adding Names

1. Last but not least we need to add the names to the diagram. For this exercise we rely on the functionalities of draw.io while using the colors from the guidelines. 
2. Starting with the L0 level the title is SAP Business Technology Platform. The color for Title is #1A2733 in hexadecimal notation. Note that you can choose different notations to enter colors in draw.io. Easiest way to change the color is just by clicking on the font color box and typing in the color code. Note that all titles should use the color #1A2733. So in the first step add all titles.
3. Now add all text elements to the diagram and use the color code #354A5F
4. Labels have the color code #5B738B. Add all labels to the diagram. Note to add labels to connections do not use the naming functionality for the connection. Instead create an own text element and add that to the connection according to your needs.
5. The diagram should finally look like this:

## Summary

You've now created your first solution diagram. We would like to encourage you to keep trying what is possible with the set of icons we provided to you by rebuilding other solution diagrams from the TechEd this year. In addition you might want to explore the differences betwen draw.io Web client and draw.io desktop. Either way we thank you for participating in this session and wish you a great remaining TechEd.

