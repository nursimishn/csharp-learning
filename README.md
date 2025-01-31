# csharp-learning
 #region while Kullanıcıdan girilen sayıları toplayan program

 int toplam = 0;
 int sayi = Convert.ToInt32(Console.ReadLine());

 int i = 1;
         
 while (i <= sayi)
 {
     toplam += i;
     Console.WriteLine("Toplam: " + toplam);
     i++;
 }

 #endregion