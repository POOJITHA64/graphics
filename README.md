# graphics
import java.awt.*;
import java.applet.*;
public class graphics demo extends applet
{
    public void paint(Graphics g)
    {
        g.drawline(10,10,20,0);
        g.drawrec(15,10,25,15);
        g.fillrec(45,10,25,15);
        g.drawroundrec(15,35,25,15,1,1);
        g.fillroundrec(45,35,25,15,33);
        set background(color.cyan);
        set foreground(color.red);
        int x={60,100,60,100,60}
        int y={60,60,100,100,60}
        int num=5;
        g.draw polygon(x,y,5);
    }
}
