import javax.swing.JFrame;
public class frame extends JFrame {
panel panel;    
public frame(){
panel = new panel();
add(panel);
setSize(500,500);// tamaño (alto,ancho)
setDefaultCloseOperation(3);//terminar el programa al cerrar
setLocationRelativeTo(null);//centrado en pantalla
}
}
