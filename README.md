# 2-D-Array
A two-dimensional array in C++ is the simplest form of a multi-dimensional array. It can be visualized as an array of arrays.
A two-dimensional array is also called a matrix. It can be of any type like integer, character, float, etc. depending on the initialization.
Initializing a 2D array in C++ :
int arr[4][2] = { {1234, 56}, {1212, 33}, {1434, 80}, {1312, 78} } ;
Printing a 2D Array in C++:
int i,j;

cout<<"Printing a 2D Array:\n";
for(i=0;i<4;i++)
{
	for(j=0;j<2;j++)<br>
	{
		cout<<"\t"<<arr[i][j];
	}
	cout<<endl;
}
