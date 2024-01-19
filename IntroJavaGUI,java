import javax.swing.*;
import java.awt.*;
import javax.swing.JLabel;
import java.awt.FlowLayout;
import java.awt.Color;

        public class IntroJavaGUI{

            public static void main (String[] args) {

                ExtendedWindowFromJFrame obj = new ExtendedWindowFromJFrame();
                // ab directly constructor se call hoga
                // kuchh hi features ke saath ayega that is already in constructor
                // additionally we can add more features here like -
                obj.getContentPane().setBackground(Color.PINK);
            }


        }

        class ExtendedWindowFromJFrame extends JFrame {
            public static int width = 400;
            public static int height = 400;

            public ExtendedWindowFromJFrame() //constructor
            {
                setLayout(new FlowLayout());
                JLabel l = new JLabel("yayyyyyy");
                JLabel l1 = new JLabel("burrraah");
                add(l);
                add(l1);

                setVisible(true); //old was obj.show()
                //by default, in JFrame class the setVisible method is set to false
                setSize(width, height);
                setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

            }


        }
