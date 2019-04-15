# SugarCalculator.java-168-
Simple code to perform calculations given a formula
/**
 * <Calculate amount of sugar needed for outside of sugar structure and colored
 * sugar for inside of sugar structure>
 *
 * @author Destini Anderson
 *
 */
public class SugarCalculator
{

	/**
	 * @param args
	 */
	public static void main(String[] args)
	{ 
		// Constants for both orders
		final double PI = 3.14159;
		final double AMOUNT_OF_SUGAR=15;
		
		// Number of Sculptures ordered for Order 1 and Order 2
		double sculpture1 = 5;
		double sculpture2 = 15;
		double sculpture3 = 5;
		
		// Sculpture test Data for Order 1
		System.out.println("Sugar Requirements for Order 1 " + "\n");
		System.out.println("Volume: " + "\n");
		
		// Sculpture 1 
		// Capsule
		double radius  = 4;
		double height  = 8;
		double volume = ((PI)*(radius*radius)*(height)+ (4.0/3)* (PI)*(radius*radius*radius));
		System.out.println("Sculpture 1");
		System.out.println("\tCapsule= " + volume );
		
		
		// Cylinder
		 radius = 5;
		 height= 12;
		 volume = (PI)*(radius*radius)*(height);
		System.out.println("\tCylinder= "+ volume + "\n");
		
		// Sculpture 2 
		//Cube
		double area = 6;
		volume = (area*area*area);
		System.out.println("Sculpture 2");
		System.out.println("\tCube= " + volume);
		
		// Ball
		radius = 2;
		volume = (4.0/3)*(PI)*(radius*radius*radius);
		System.out.println("\tBall= " + volume + "\n");
				
		// Sculpture 3
		// Rectangle
		double length = 16;
		double width  = 6;
		height = 7;
		volume = (length*width*height);
		System.out.println("Sculpture 3");
		System.out.println("\tRectangle= " + volume );
		
		// Cylinder
		radius  = 2;
		height= 5;
		volume = ((PI)*(radius*radius*radius)* (height));
		System.out.println("\tCylinder= " + volume + "\n" );
		
		// Amount of white sugar for each sculpture for Order 1
	
		System.out.println("White Sugar Amount:" );
		System.out.println("\tSculpture 1= " + (272.271*AMOUNT_OF_SUGAR*sculpture1) );
		System.out.println("\tSculpture 2= " + (182.49*AMOUNT_OF_SUGAR*sculpture2));
		System.out.println("\tSculpture 3= " + (546.336*AMOUNT_OF_SUGAR*sculpture3 + "\n"));
		
		//Amount of colored sugar
		System.out.println("Colored Sugar Amount:" );
		System.out.println("\tSculpture 1= " + (670.2058666666667*AMOUNT_OF_SUGAR*sculpture1) );
		System.out.println("\tSculpture 2= " + (216.0*AMOUNT_OF_SUGAR*sculpture2));
		System.out.println("\tSculpture 3= " + (125.6636*AMOUNT_OF_SUGAR*sculpture3 + "\n"));
		
		// Sculpture test Data for Order 2
		System.out.println("Sugar Requirements for Order 2 " + "\n");
		System.out.println("Volume: " + "\n");
		
		// Sculpture 1 
		// Capsule
		 radius  = 5;
		 height  = 9;
		 volume = ((PI)*(radius*radius)*(height)+ (4.0/3)* (PI)*(radius*radius*radius));
		System.out.println("Sculpture 1");
		System.out.println("\tCapsule= " + volume );
		
		
		// Cylinder
		 radius = 7;
		 height= 14;
		 volume = (PI)*(radius*radius)*(height);
		System.out.println("\tCylinder= "+ volume + "\n");
		
		// Sculpture 2 
		//Cube
		 area = 12;
		volume = (area*area*area);
		System.out.println("Sculpture 2");
		System.out.println("\tCube= " + volume);
		
		// Ball
		radius = 4;
		volume = (4.0/3)*(PI)*(radius*radius*radius);
		System.out.println("\tBall= " + volume + "\n");
				
		// Sculpture 3
		// Rectangle
		 length = 12;
		 width  = 10;
		height = 7;
		volume = (length*width*height);
		System.out.println("Sculpture 3");
		System.out.println("\tRectangle= " + volume );
		
		// Cylinder
		radius  = 1;
		height= 3;
		volume = ((PI)*(radius*radius*radius)* (height));
		System.out.println("\tCylinder= " + volume + "\n" );
		
		// Amount of White sugar for order 2
		System.out.println("White Sugar Amount:" );
		System.out.println("\tSculpture 1= " + (2155.13*AMOUNT_OF_SUGAR*sculpture1) );
		System.out.println("\tSculpture 2= " + (1459.92*AMOUNT_OF_SUGAR*sculpture2));
		System.out.println("\tSculpture 3= " + (830.575*AMOUNT_OF_SUGAR*sculpture3) + "\n");
		
		//Amount of colored sugar
		System.out.println("Colored Sugar Amount:" );
		System.out.println("\tSculpture 1= " + (1230.4560833333333*AMOUNT_OF_SUGAR*sculpture1) );
		System.out.println("\tSculpture 2= " + (268.08234666666664*AMOUNT_OF_SUGAR*sculpture2));
		System.out.println("\tSculpture 3= " + (840.0*AMOUNT_OF_SUGAR*sculpture3) + "\n");
		
		//Total white sugar needed
		System.out.println("Total White Sugar Needed = 654865.65"  );
		System.out.println("Total Colored Sugar Needed = 215602.74");
		
		
	}
}
