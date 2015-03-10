'''
Question 3: See specification on exam paper.

@author: Min Song
'''
from zellegraphics import *

def drawTangentCircles(win, bottomPoint, radiusDifference, nCircles):
    ''' win: the graphical window  
        bottomPoint: the Point at the bottom of the tangent circles
        radiusDifference: how much the radius changes each time as the circles increase in size
        nCircles: the number of circles to draw
    '''    
    #DONE: 1 Replace the pass with your code
    for i in range(nCircles):
        center = Point(bottomPoint.getX(), bottomPoint.getY() - radiusDifference * (i + 1))
        tanCirc1 = Circle(center, radiusDifference * (i + 1))
        
        if i % 2 == 0:
            tanCirc1.setOutline("red")
        tanCirc1.draw(win)
    
    

def main():            
    win = GraphWin("Test", 400, 400)
    drawTangentCircles(win, Point(200, 200), 15, 5)
    #DONE: 2 uncomment these when you are ready for more testing. You may add more tests if you like.
    drawTangentCircles(win, Point(300, 300), 6, 10)
    drawTangentCircles(win, Point(100, 350), 3, 25)
    win.getMouse()
    win.close()

main()
    
