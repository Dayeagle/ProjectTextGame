#include <iostream>
#include <string>
#include <sstream>

using namespace std;

int main(){

	string input = "";

		cout << "BEM VINDO!!\n";
		cout << "\nVoce esta em uma floresta, a oeste existe uma casa \ne a mesma tem uma porta de entrada.\n";
		cout << "Aos seus pes existe uma caixa.\n";
		cout << "O que voce deseja fazer?\n";
		getline(cin, input);

		if (input == "avancar"){

			cout << "Funcionou";\

		}
		if (input == "pegar caixa"){
			cout << "Voce pegou a caixa\n";
			getline(cin, input);

			if (input == "abrir caixa"){
				cout << "dentro da caixa voce encontra uma folha.  Nesta folha diz: \n";
				cout << "Bem vindo ao meu mundo. Siga minhas regras e tente sobreviver.\n";
				cout << "\n O que deseja fazer agora?\n";
				getline(cin, input);

			}
		}
		

		else{
			cout << "Comando nao reconhecido";
		}

		system("PAUSE");
		return 0;


}
