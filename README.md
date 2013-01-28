work
===
public static void main(String args[]){
  JFrame f = new JFrame("my new Swing");
  Dimension d =new Dimension();
  d.setSize(350,90);
  f.setSize(d);
  f.setBackgrond(Color.WHITE);
  Point p=new Point(500,500);
  f.setLocation(p);
  f.setVisible(true);
}
