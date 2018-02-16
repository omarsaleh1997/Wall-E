from OpenGL.GL import *
from OpenGL.GLU import *
from OpenGL.GLUT import *
def draw():
    glColor(1, 1, 1)

    glBegin(GL_POLYGON)
    glVertex2d(0.3, -0.3)
    glVertex2d(0.3, 0.3)
    glVertex2d(-0.3, 0.3)
    glVertex2d(-0.3, -0.3)

    glEnd()
   
    glFlush()  


    glColor(1, 1, 1)

    glBegin(GL_POLYGON)
    glVertex2d(0.1, 0.3)
    glVertex2d(0.1, 0.4)
    glVertex2d(-0.1, 0.4)
    glVertex2d(-0.1, 0.3)

    glEnd()
    
    glFlush()  


    glColor(1, 1, 1)

    glBegin(GL_POLYGON)
    glVertex2d(0.2, 0.4)
    glVertex2d(0.2, 0.8)
    glVertex2d(-0.2, 0.8)
    glVertex2d(-0.2, 0.4)

    glEnd()
    glFlush()  



    glColor(1, 0, 0)

    glBegin(GL_POLYGON)
    glVertex2d(0.05, 0.45)
    glVertex2d(0.05, 0.5)
    glVertex2d(-0.05, 0.5)
    glVertex2d(-0.05, 0.45)

    glEnd()
    
    glFlush()  


    glColor(1, 0, 0)

    glBegin(GL_POLYGON)
    glVertex2d(0.15, 0.65)
    glVertex2d(0.15, 0.75)
    glVertex2d(0.05, 0.75)
    glVertex2d(0.05, 0.65)

    glEnd()
    
    glFlush()  

    glColor(1, 0, 0)

    glBegin(GL_POLYGON)
    glVertex2d(-0.15, 0.65)
    glVertex2d(-0.15, 0.75)
    glVertex2d(-0.05, 0.75)
    glVertex2d(-0.05, 0.65)

    glEnd()
    
    glFlush()  

    glColor(0, 0, 1)

    glBegin(GL_POLYGON)
    glVertex2d(0.4, -0.2)
    glVertex2d(0.4, 0.2)
    glVertex2d(0.3, 0.2)
    glVertex2d(0.3, -0.2)

    glEnd()
    
    glFlush()  
    glColor(0, 0, 1)

    glBegin(GL_POLYGON)
    glVertex2d(-0.4, -0.2)
    glVertex2d(-0.4, 0.2)
    glVertex2d(-0.3, 0.2)
    glVertex2d(-0.3, -0.2)

    glEnd()
   
    glFlush()  

    glColor(0, 0, 1)

    glBegin(GL_POLYGON)
    glVertex2d(0.2, -0.9)
    glVertex2d(0.2, -0.3)
    glVertex2d(0.1, -0.3)
    glVertex2d(0.1, -0.9)

    glEnd()
 
    glFlush()  

    glColor(0, 0, 1)

    glBegin(GL_POLYGON)
    glVertex2d(-0.2, -0.9)
    glVertex2d(-0.2, -0.3)
    glVertex2d(-0.1, -0.3)
    glVertex2d(-0.1, -0.9)

    glEnd()
   
    glFlush()  

glutInit()
glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
glutInitWindowSize(900, 900)
glutCreateWindow(b"WALL_E")
glutDisplayFunc(draw)
glutMainLoop()
