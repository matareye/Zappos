Zappos
======

#include<iostream>
#include<cmath>
#include<string>

using namespace std;

int main()
{

int N, X;
char category;

cout << "Please enter the most you are willing to spend." << endl;
cin>>X;
cout << endl;
cout << "Please enter the quantity." << endl;
cin >> N;
cout << "Please enter the category which you would like to purchase the item from." << endl;
cin >> category;

/Search/term/category?includes=["facets"]&facets=["productTypeFacet","price"]

/*
{
"facetField": "priceFacet",
"facetFieldDisplayName": "price",
"values":
[
{
"name":"150.00 and under",
"count":40
}
]
}
*/


return 0;
}
