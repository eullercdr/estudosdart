### Condições e Operadores

```dart
  void main() {
  
    double nota = 7.0;
    
    if(nota < 5.0){
      print ("Exame");
    }
    else if (nota ==9.9)
    {
      print("Quase Sucesso Total");
    }
    else {
      print ("Sucesso :-)")
    }
}
```
### Operador Ternário
```dart
void main() {
  
    double nota = 7.0;
    
    if(nota < 5.0){
      print ("Exame");
    }
    else if (nota ==9.9)
    {
      print("Quase Sucesso Total");
    }
    else {
      print ("Sucesso :-)");
    }
    
    bool aprovado = true;
    String info;
    
    info=aprovado ? "Aprovado" : "Reprovado";
	print(info);
}

```

