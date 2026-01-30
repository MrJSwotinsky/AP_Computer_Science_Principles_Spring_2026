## Unit 0, Assignment 2 - Exploring Group Properties
Due: Monday, February 2nd 2026

### Explore Group Properties and Report Your Findings

1.  In your CMU Graphics canvas, create a new group image.
  * Remember to assign each shape to a variable.
  * Remember to group your shapes and assign your group to a variable.   
    <br>*For example,* <br><img src = 'https://github.com/MrJSwotinsky/AP_Computer_Science_Principles_Spring_2026/blob/main/Resources/Car.png'> 
    ```python
    front_wheel = Circle(275, 250, 30)
    back_wheel = Circle(125, 250, 30)
    bottom = Rect(50, 150, 300, 100, fill='Red')
    top = Polygon(100, 150, 300, 150, 250, 100, 150, 100,fill = 'Red')
    car = Group(front_wheel, back_wheel, bottom, top)
    ```

2.  Add an `onMousePress()` event to explore how you can modify shape properties for your group by clicking the mouse.
<br><br>*For example,*
    ```python
    def onMousePress(mouseX, mouseY):
        car.centerX += 10
    ```
3.  Explore with a variety of different [`shape properties`](https://academy.cs.cmu.edu/docs/generalShapeProperties), such as...

* `left`, `right`, `top`, `bottom`, `centerX`, `centerY`
* `width`, `height`
* `fill`, `opacity`
* `rotateAngle`
* `visible`
    
4.  Use code comments to document at least 5 discoveries. 
<br><br>*For example,*
    ```python
    # I can use the command, car.rotate = 45, to rotate my group 45 degrees clockwise around its center.
    ```
5. Create a file in your assignments folder titled `LastNameFirstInitial_Exploring_Group_Properties.py`
6. Copy/Paste your code from the sandbox to `LastNameFirstInitial_Exploring_Group_Properties.py`.
7. Commit your work.

     **Remember to include an appropriate commit message**.
