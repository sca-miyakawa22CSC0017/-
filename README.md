# -
全然ちゃんとできていない課題

#include <iostream>
#include <string>
using std::cin;
using std::cout;
using std::endl;
using std::string;

int main() {
  const int GOLD_PIECES = 900;
  string leader;
  int adventures, killed, survivors;
  //情報を取得する
  cout << "今から冒険へ出かけましょう！\n\n";
  cout << "パスワードを入力してください\n";

  // cout << "Enter a number:";
  cin >> adventures;

  cout << "\n古代のお宝を目指し5人、冒険者を集い旅にでました ";
  cout << "途中アクシデントに5回あいました.\n";
  cout << "その旅もすぐに終わりを迎えました";
  cout << "自分以外の冒険者がすべて逃げてしまったのです";
  cout << "ですが自分１人でも夢だった古代のお宝を目指し旅をつづけました\n";
  cout << "そしてついに古代のお宝を見つけました。";
  cout << "終わり";

  return 0;
}
