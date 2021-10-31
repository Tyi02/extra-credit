# extra-credit
package CSCI125hw;

public class item {
	String name;
	String color;
	String rarity;
	int level;
	
public void common() {
	System.out.println("Congratulation "+name+" is common, lvl 1!");
}
	public void rare() {
		System.out.println("Congratulations "+name+" is rare, lvl 12!");
}	
public void legendary() {
	System.out.println("Congratulations "+name+" is Legendary, lvl 50!!!");
}
public void Exotic() {
	System.out.println( "Congratulations "+name+" is Exotic, lvl 100!!!!!");
}

	
	
	public item(String name1, int lvl) {
	name = name1;
	level = lvl;
	}
	
		
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		item i1 = new item("sword", 1);
		i1.name= "sword";
		
		
		item i2 = new item("shield", 12);
		i2.name= "shield";
		
		
		item i3 = new item("bow", 50);
		i3.name= "bow";
		
		
		item i4 = new item("staff", 100);
		i4.name= "staff";
		
		
		i1.common();
		i2.rare();
		i3.legendary();
		i4.Exotic();
	}
}
