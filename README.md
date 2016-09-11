# Role-Playing
//Johnathan Mata  //September 10, 2016 

public class Item
{
  String name;
  void setName (String n) 
  {
    name = n;
  }
  String getName()
  {
    return name;
  }
}
class Weight 
{
  String weight;
  void setWeight (String w)
  {
    weight = w;
  }
  String getWeight()
  {
    return weight;
  }
}
*****
public class ItemBeta
{
  public static void main (String[] args)
  {
    Item i = new Item();
    i.setName("Johnathan");
      String John = i.getName();
    System.out.println("name:" + John);
   }
}
