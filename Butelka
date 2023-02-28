public class Butelka{
    
    double ileLitrow; /* this.ileLitrow */
    double pojemnosc;
  
  Butelka(double ileLitrow, double pojemnosc) /* konstruktor*/
        {
            this.ileLitrow = ileLitrow;
            this.pojemnosc = pojemnosc;
        }
        
        double getIleLitrow()
        {
            return ileLitrow;
        }
        
        void wlej(double ilosc) /* metoda odpowiedzialna za wlewanie - stworzona zostala zmienna "ilosc" */
        {
            this.ileLitrow += ilosc;
        }
        
        boolean wylej(double ilosc) /* metoda odpowiedzialna za wylewanie */
        {
            if (ilosc < ileLitrow)
                this.ileLitrow -= ilosc;
                
              else 
                  return false;
            
            return true;
        }
        
        void przelej (double ilosc, Butelka gdziePrzelac) /* double ilosc - ile mamy przelac, Butelka gdziePrzelac - zmienna typu Butelka i nazwa gdziePrzelac */
        {
                if (this.wylej(ilosc))
                {
                    gdziePrzelac.wlej(ilosc); /* wywołujemy gdziePrzelac i dopisujemy metode "wlej" */
                }
                else 
                
                    System.out.println("Za mało");
                    
            
    }
    
    
    public static void main(String args[]) {
            Butelka[] butelka = new Butelka[3];
        
            butelka[0] = new Butelka(5, 10); /* wartosc na podstawie konstruktora "Butelka(double ileLitrow, double pojemnosc) - konstruktor"*/
            butelka[1] = new Butelka(8, 12);
            butelka[2] = new Butelka(12, 35);
            
            
            
butelka[0].wlej(0); /* wywołanie metody doKtorejButelki wlewamy.wlej(double ilosc - 4 ) */
	    butelka[0].przelej (5, butelka[1]); /* wywolana metoda przelej z butelki [0], przelewamy ilosc np. 3, do której butelki np. buteli[1] - butelki według tablicy */
            
            System.out.println(butelka[0].getIleLitrow()); /* getIleLitrow - wziete z metody stworzonej wyzej */
            System.out.println(butelka[1].getIleLitrow());
            System.out.println(butelka[2].getIleLitrow());
        
        
    }
}
            
        
