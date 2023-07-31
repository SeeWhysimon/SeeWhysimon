//exercise 5.20

#include <iostream>
#include <vector>

using namespace std;

int main()
{
	string preword = "", word = "";
	int cnt = 0;

	while (cin >> word) {
		if (word == preword) {
			++cnt;
			break;
		}
		else preword = word;
	}
	if (cnt == 0) cout << "no word was repeated" << endl;
	else cout << preword << " repeated twice" << endl;
	return 0;
}

//exercise 5.24

#include <iostream>

using namespace std;

int main()
{
	double a, b;
	while (cin >> a >> b) {
		try {
			if (b != 0)
				cout << a/b << endl;
			else
				throw runtime_error("number divided by 0");
		}
		catch (runtime_error err) {
			cout << err.what() << "\nTry Again? Enter y or n" << endl;
			char c;
			cin >> c;
			if (!cin || c == 'n')
				break;
		}
	}
	return 0;
}

//exercise 7.12

sales_data(std::istream& is) { read(is, *this); }

//exercise 7.31

class Y;

class X {
	Y* ptr;
};

class Y {
	X obj_x;
};
