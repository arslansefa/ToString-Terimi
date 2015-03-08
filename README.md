# ToString-Terimi
ToString Terimi Nedir?
public String toString() metodu Java'da tum metodlarin turedigi en tepedeki sinif olan Objet'in bir metodudur. Herhangi bir nesne icinde bu metodu yazarsaniz nesnenin iceriginin size nasil gorunmesine iliskin bir kod yazmaniz beklenir. Örneğin;
   

public class StringTest
{
    private String ad = "Mehmet";
    private String soyad = "EMEK";

    public String toString()
    {
        return "Adi:" + ad + " Soyadi:" + soyad;
    }

    public static void main(String[] args)
    {
        StringTest test = new StringTest();
        System.out.println("to String sonucu: " + test.toString());
    }
}
  onucta ekranda "to String sonucu: Adi:Mehmet Soyadi:EMEK" yazdigini goreceksiniz.
