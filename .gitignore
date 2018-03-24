#include <fstream>
#include <iostream>
#include <string>
using namespace std;


int main() {
	int n, x, y;
	const int width = 15;
	const int height = 15;
	string slova[4];
	basic_string <char>::size_type size;
	cin >> n;
	//-------------------------
	for (int i = 0; i < n; i++)
		cin >> slova[i];
	for (int i = 0; i < n; i++) {
		size = slova[i].size();
		if (slova[i + 1].size() > slova[i].size());
			cout << slova[i + 1];
		cout << slova[i].size() << endl;
	}
	//--------------------------
	for (int i = 0; i < width + 1; i++) cout << "-"; cout << endl; //Вверхняя граница.

	for (int i = 0; i < height; i++) {
		for (int j = 0; j < width; j++) {
			if (j == 15) {
				cout << "|";//Граница сбоку(Слева и Справа).
			}
			cout << " "; // Заполнение поля - пустыми полями.
			cout << endl;
		}
	}

	for (int i = 0; i < width + 1; i++)cout << "-"; //Нижняя граница.
	//-------------------------------
	system("pause");
	return 0;
}
