# hello-world
#include<iostream>
using namespace std;
int main()
{
	/*The first box braces contain the number of rows in the array*/
	/*The second braces contain the numbers of columns in the array*/
	int numbers[3][4] ={ 
		{0, 1, 2, 3}, 
		{4, 5, 6, 7}, 
		{8, 9, 10, 11} 
	};
	//to output a specific element in the array, you put in the row of the element and the column
	cout<<numbers[2][3]<<endl; 
	//to output all the elements in the array, use a nested for loop
	for (int row = 0; row < 3; ++row)
	{
	  for (int column = 0; column < 4; ++column)
	  {
	  	cout<<numbers[row][column]<<" "; 
	  }
	  cout<<endl;
	}



	return 0;
}
