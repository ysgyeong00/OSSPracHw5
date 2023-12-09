#include <iostream>
using namespace std;

class PrintKorean {
public:
	string korean;
	void PK();
};

void PrintKorean::PK() {
	for (int i = 0; i < size(korean); i++) {
		cout << korean[i];
	}
}

int main() {
	string name;
	int stdnum;
	string major;
	int grade;

	cout << "이름을 입력하세요 : ";
	cin >> name;
	cout << "학번을 입력하세요 : ";
	cin >> stdnum;
	cout << "학과를 입력하세요 : ";
	cin >> major;
	cout << "학년를 입력하세요 : ";
	cin >> grade;

	PrintKorean Name;
	Name.korean = name;
	PrintKorean Major;
	Major.korean = major;

	cout << "\n<출력>";
	cout << "\n이름 : ";
	Name.PK();
	cout << "\n학번 : " << stdnum;
	cout << "\n학과 : ";
	Major.PK();
	cout << "\n학년 : " << grade;
	cout << "\n";

	return 0;
}
