```cpp
#include <iostream>

class CRect {
private:
	int wid, hig;
public:
	int Area() { return wid * hig;}
	CRect(int a, int b);
};
CRect::CRect(int a, int b) {
	wid = a;
	hig = b;
}

		int main() {
			CRect r(3, 4);
				std::cout << r.Area();
		}
```
