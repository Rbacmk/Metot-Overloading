# Metot-Overloading
 //  Metot Overloading
            // Out Parametreler
            string sayi = "999";
          bool sonuc=  int.TryParse(sayi, out int outSayi);
            if(sonuc)
            {
                Console.WriteLine("Başarılı");
                Console.WriteLine(outSayi);
            }
            else
            {
                Console.WriteLine("Başarısız");
            }

        }
