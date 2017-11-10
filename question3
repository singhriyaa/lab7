# include <iostream>
using namespace std;

class rectangle{
	public:
	double len;
	double bre;
	double area(double len,double bre){
		return len*bre;
	}

	double perimeter(double len, double bre){
		return 2*(len+bre);
	}
};

int main()
{ double len,bre,area1,area2,perimeter1,perimeter2;
  rectangle r1;
  rectangle r2;
 
  cout<<"\nEnter the length and breadth of rectangle 1.";
  cin>>r1.len;
  cin>>r1.bre;
  perimeter1=r1.perimeter(r1.len,r1.bre);
  area1=r1.area(r1.len,r1.bre);
 
  cout<<"\nEnter the length and breadth of rectangle 2.";
  cin>>r2.len;
  cin>>r2.bre;
  perimeter2=r2.perimeter(r2.len,r2.bre);
  area2=r2.area(r2.len,r2.bre);
 
  cout<<"\nArea of rectangle 1 is "<<area1;
  cout<<"\nArea of rectangle 2 is "<<area2;
  cout<<"\nPerimeter of rectangle 1 is "<<perimeter1;
  cout<<"\nPerimeter of rectangle 2 is "<<perimeter2;
 
  {if(perimeter1 > perimeter2) 
 cout<<"\nRectangle 1 has larger perimeter.";
 else if(perimeter2 > perimeter1)
 cout<<"\nRectangle 2 has larger perimeter.";
 
else if(perimeter1==perimeter2)
 cout<<"\nBoth the rectangles have equal perimeter.";}

 {if(area1 > area2) 
 cout<<"\nRectangle 1 has larger area.";
 else if(area2 > area1)
 cout<<"\nRectangle 2 has larger area.";
 
else if(area1==area2)
 cout<<"\nBoth the rectangles have equal perimeter.";}
 
  return 0;
}
