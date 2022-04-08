# Codeforcescpp-49A
#include <bits/stdc++.h>
using namespace std;

int main() {
	string s;
  int tmp;
  getline(cin,s);
  string vowels = "aeiouyAEIOUY";
  int i = s.size()-1;
  while(i--){
    if(s[i]!=' '){
      if(vowels.find(s[i])!=vowels.npos)
        cout << "YES";
      else
        cout << "NO";
      return 0;
    }
  }
	return 0;
}
