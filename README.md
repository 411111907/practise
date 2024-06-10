# practise
#include <iostream>
using namespace std;

int main() {
    int N;
    cin >> N; // 讀取第一行的整數N
    for (int i = 0; i < N; ++i) {
        int number;
        cin >> number; // 讀取每一行的整數
        if (number % 2 == 0) {
            cout << "偶數" << endl; // 偶數
        } else {
            cout << "奇數" << endl; // 奇數
        }
    }
    return 0;
}
