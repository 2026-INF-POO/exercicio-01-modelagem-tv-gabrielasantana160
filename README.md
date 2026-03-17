class TV {

    int tamanhoTela; 
    int volume = 5;
    String marca; 
    int voltagem; 
    int canal; 

    void ligar() {
        int consumo = voltagem * tamanhoTela;
 }


    void desligar() {
    }


    void aumentarVolume() {
        volume++;
    }

    
    void diminuirVolume() {
        volume--;
    }

    
    void subirCanal() {
        canal++;
    }

    
    void descerCanal() {
        canal--;
    }
}
