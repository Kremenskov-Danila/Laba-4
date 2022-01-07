//Task 1.

#include <iostream>
using namespace std;
int main()
{
    setlocale(LC_ALL, "rus");
    int n, i;
    float a[50], sum=0;
    cout << "Введите размерность:\n";
    cin >> n;
    cout << "Введите массив:\n";
    cin >>a[n]
    for (i=0; i<n; i++)
        cin >> a[i];
    for (i=0; i<n; i++)
        sum+=a[i];
    cout << "Среднее арифметическое:\n" << sum/n << endl;
    system("pause");
    return 0;
}

//Task 2.

#include <iostream>
#include <cstdlib>

using namespace std;

int N;
std::numeric_limits<int N>::min(1)); 
std::cin >> N; 

int main() 
{
	int mass[N], max, min;

	std::numeric_limits<int >::max());

	cout << "Элементы: |";
	for(int r = 0; r<N; r++)
	{
		mass[r] = rand()%99;
		cout << mass[r] << "|";
	}
	cout << endl;
	
	max = mass[0];
	min = mass[0];
	for(int r = 1; r<N; r++)
	{
		if(max < mass[r]) max = mass[r];
		if(min > mass[r]) min = mass[r];
	}
	cout << "Min: " << min << endl;
	cout << "Max: " << max << endl;
	
	return 0;
}

//Task 3.

#include "stdafx.h"
#include <iostream>
using namespace std;
int main() {
  int maxI,max, N;
  std::numeric_limits<int N>::min(0)); 
  std::cin >> N;
  if (N = 0) {
	  cout<<"-1"<< endl;
  }
  if (N > 0) {
  int array[N];
  
    for(int i = 0; i < N; i++) {
      cin >> array[i];
    }
 
  max = array[0];
  for(int i = 0; i < 12; i++){
   if (array[i] > max) {
        max = array[i];
        maxI = i;
       }
  }
  cout << maxI;
}
//Task 4.

#include <iostream>

using namespace std;

int main()
{
 int n; 
 cout << "Количество элементов: ";
 cin >> n; 
	
 int mass[n];
 for(int i = 0; i < n; ++i)
 {
  cout << i+1 << "-ый элемент: ";
  cin >> mass[i]; 
 } 
	
 for(int i = 1; i < n; ++i)
 {
  for(int r = 0; r < n-i; r++)
  {
   if(mass[r] < mass[r+1])
   {
    int temp = mass[r];
    mass[r] = mass[r+1];
    mass[r+1] = temp;
   }
  }
 }	
 
 cout << "Отсортированный массив: ";
 for(int i = 0; i < n; ++i)
 {
  cout << mass[i] << " ";
 }
 cout << endl;
 return 0;
}

//Task 5.

#include<iostream>
using namespace std;
int main() 
{
    std::cin >> N;
    int mass[N];
    int k, l;
    int *removed_element;
    for (int i = 0; i < N; i++) 
    {
        cout << "[" << i + 1 << "]" << ": ";
        cin >> mass[i];
    }
    for (int i = 0; i < N; i++) 
    {
        if (mass[i] < 0) 
        {
            *removed_element = &mass[i];
            std::cout << "True" << endl;
            break;
        } 
        else
            l = 0;
            *removed_element = &l;
            std::cout << "False" << endl;
    } 
    for (int i = 0; i < n; i++) 
        cout << mass[i] << " " << endl;
    return 0;
}

//Task 6.

#include <iostream>
#include <string>
#include <clocale>
using namespace std;
 
int main()
{
    setlocale(LC_ALL, "");
 
    std::cout << const std::string& str << endl;
    std::cout << const std::string& old << endl;
    std::cout << const std::string& new << endl;
 
    size_t pos = 0, cnt = 0;
    
    while ((pos = str.find(string& old, pos)) != string::npos)
    {
        str.replace(pos, const std::string& old.size(), string& new);
        pos += const std::string& new.size();
    }
}

//Task 7.

#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <string>
#include <iostream>
using namespace std;
 
int main()
{
    setlocale(LC_ALL, "Russian");
    char str[500];
    cout << "Введите строку: ";
    cin.getline(str, sizeof(str));
 
    char delv[10];
    cout << "Введите разделитель: ";
    cin.getline(delv, sizeof(delv));
 
    char* token = strtok(str, delv);
    while (token != NULL)
    {
        printf("%s\n", token);
        token = strtok(NULL, delv);
    }
    return 0;
}

//Task 8.
#include "stdafx.h"
#include <iostream>
#include <string>
#include <cstring>

using namespace std;
int main()
{
    int m, n;
    std::cin >> m;
    std::cin >> n;
    char Str[m][n];
    std::string new_str;
    cout << "Введите размерность:\n";
    cin >> m >> n;
    cout << "Введите массив:\n";
    cin >>Str[m][n]
    for(int m = 1, Str[m] !=0; m++) {
        new_str += Str[m]
    }
}
