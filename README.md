# dio-lab-flutter-create

Um flutter contador padrão. Com o objetivo inicial de abordar alguns parametros de criação de projetos flutter.

Criado a partir do seguinte comando:
```sh
flutter create --project-name dio_lab_flutter_create -t app --platforms android --org com.mizzaelcosta.dio-lab-flutter-create -a kotlin ./dio_lab_flutter_create
```
* [--project-name] atribui nome ao projeto atual [dio_lab_flutter_create]. Deve ser um nome de pacote Dart válido. Veja [pubspec#name](https://dart.dev/tools/pub/pubspec#name) pra mais detalhes.

* [-t][--template] especifica o tipo de projeto a ser criado, onde [app] gera uma aplicação flutter

* [--platforms] especifica as plataformas suportadas no projeto, nesse em específico suportará apenas [android]. Parametro válido apenas para templates do tipo [app] e [plugin]

* [--org] organização responsável pelo projeto flutter. Notação em dominio reverso [com.mizzaelcosta.dio-lab-flutter-create].

* [--project-name] nome atribuido ao projeto atual. Deve ser um nome de pacote Dart válido.

* [-a][--android-language] linguagem usada em codigo especifico à plataforma android, neste será usada [kotlin]. 

* [./dio_lab_flutter_create] diretório de saída, onde serão colocados arquivos e pasta do projeto atual.


Vale Lembrar que o único parâmetro obrigatório ao comando [create] é o diretótio de saída, os demais são opcionais. Os parâmetros opcionais ajudam a especificar carcteristicas ao projeto, no momento de sua criação.

```sh
flutter create dio_lab_flutter_create
```

## Como executar

1. clone o repisitório.
   ```sh
   git clone https://github.com/MizzaelCosta/dio-lab-flutter-create.git
   ```
   
2. instale as dependencias:
 
   ```sh
   flutter pub get
   ```
   
3. execute: (necessário um emulador android instalado ou um dispositivo conectado)
   ```sh
   flutter run
   ```   
