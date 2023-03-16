# Laba-1
Завдання 1 
public class First {public static void main (String args[])

    int a = 100;
    int b = 90;
    int c = 80;
    int d = 70;
    int e = 60;
    int f = 50;
    int g = 40;
    int h = 30;
    int i = 20;
    int j = 10;

    int p = a + b + c + d + e + f + g + h + i + j;
    int o = a - b - c - d - e - f - g - h - i - j;
    int x = a * b * c * d * e * f * g * h * i * j;
    float y = a / b / c / d / e / f / g / h / i / j;

    System.out.printf("Сума = %d\n Різниця = %d\n Добуток = %d\n Частка = %.20f",p, o, x,y);
}
}

Завдання 2 
public class Second {
    public static void main (String args[]){
        String a = "Як";
        String b = "умру";
        String c = "то";
        String d = "поховайте";
        String e = "мене";
        String f = "на";
        String g = "могилі";
        String h = "серед";
        String i = "степу";
        String j = "широкого";

        System.out.printf("%s %s %s %s %s %s %s %s %s %s",a,b,c,d,e,f,g,h,i,j);
    }
}
 
 Завдання 3 
 public class Third {
    public static void main(String args[]) {
        int id = 1;
        int age = 20;
        String name = "Андрій";
        String surname = "Лавер";
        double weight = 75.3;
        double height = 1.69;

        int id1 = 2;
        int age1 = 18;
        String name1 = "Назар";
        String surname1 = "Боруто";
        double weight1 = 66.8;
        double height1 = 1.78;

        int id2 = 3;
        int age2 = 43;
        String name2 = "Володимир";
        String surname2 = "Зеленський";
        double weight2 = 65.0;
        double height2 = 1.67;

        int id3 = 4;
        int age3 = 19;
        String name3 = "Саске";
        String surname3 = "Учіха";
        double weight3 = 60.7;
        double height3 = 1.78;

        int id4 = 5;
        int age4 = 16;
        String name4 = "Наруто";
        String surname4 = "Удзумакі";
        double weight4 = 68.2;
        double height4 = 1.83;

        int id5 = 6;
        int age5 = 19;
        String name5 = "Лідія";
        String surname5 = "Ярема";
        double weight5 = 62.4;
        double height5 = 1.74;

        int id6 = 7;
        int age6 = 17;
        String name6 = "Євген";
        String surname6 = "Сєрий";
        double weight6 = 60.0;
        double height6 = 1.76;

        int id7 = 8;
        int age7 = 18;
        String name7 = "Сергій";
        String surname7 = "Звенигора";
        double weight7 = 61.3;
        double height7 = 1.87;

        int id8 = 9;
        int age8 = 19;
        String name8 = "Ілля";
        String surname8 = "Іллін";
        double weight8 = 76.8;
        double height8 = 1.72;

        int id9 = 10;
        int age9 = 17;
        String name9 = "Климентій";
        String surname9 = "Косовий";
        double weight9 = 65.0;
        double height9 = 1.76;

        int sumage = age + age1 + age2 + age3 + age4 + age5 + age6 + age7 + age8 + age9;

        double sumweight = weight + weight1 + weight2 + weight3 + weight4 + weight5 + weight6 + weight7 + weight8 + weight9;

        double sumheight = height + height1 + height2 + height3 + height4 + height5 + height6 + height7 + height8 + height9;

        System.out.printf("Сума їх віку = %d років\n Сума їх ваги = %.2f кг\n Сума їх зросту = %.2f м",sumage, sumweight, sumheight);
    }
}

Завдання 4 
public class Fourth {
    public static void main(String args[]) {
        int power1 = 478;
        int volume1 = 120;
        int maxspeed1 = 300;
        double wheelradius1 = 1.6;
        double leight1 = 4.4;
        double weight1 = 1100;
        String color1 = "Blue";

        int power2 = 400;
        int volume2 = 110;
        int maxspeed2 = 290;
        double wheelradius2 = 1.6;
        double leight2 = 4.0;
        double weight2 = 1200;
        String color2 = "Silver";

        int power3 = 489;
        int volume3 = 130;
        int maxspeed3 = 320;
        double wheelradius3 = 1.7;
        double leight3 = 4.1;
        double weight3 = 1100;
        String color3 = "Orange";

        int power4 = 478;
        int volume4 = 120;
        int maxspeed4 = 300;
        double wheelradius4 = 1.6;
        double leight4 = 4.4;
        double weight4 = 1100;
        String color4 = "Blue";

        int power5 = 376;
        int volume5 = 80;
        int maxspeed5 = 265;
        double wheelradius5 = 1.8;
        double leight5 = 4.5;
        double weight5 = 1150;
        String color5 = "Red";

        int power6 = 480;
        int volume6 = 100;
        int maxspeed6 = 290;
        double wheelradius6 = 1.6;
        double leight6 = 4.6;
        double weight6 = 1400;
        String color6 = "Blue";

        int power7 = 400;
        int volume7 = 75;
        int maxspeed7 = 280;
        double wheelradius7 = 1.6;
        double leight7 = 4.3;
        double weight7 = 1100;
        String color7 = "White";

        int power8 = 396;
        int volume8 = 90;
        int maxspeed8 = 290;
        double wheelradius8 = 1.7;
        double leight8 = 4.5;
        double weight8 = 1200;
        String color8 = "Red";

        int power9 = 400;
        int volume9 = 110;
        int maxspeed9 = 290;
        double wheelradius9 = 1.6;
        double leight9 = 4.0;
        double weight9 = 1200;
        String color9 = "Silver";

        int power10 = 357;
        int volume10 = 100;
        int maxspeed10 = 260;
        double wheelradius10 = 1.5;
        double leight10 = 4.2;
        double weight10 = 1300;
        String color10 = "Red";

        int sumpower = power1 + power2 + power3 + power4 + power5 + power6 + power7 + power8 + power9 + power10;

        double sumvolume = volume1 + volume2 + volume3 + volume4 + volume5 + volume6 + volume7 + volume8 + volume9 + volume10;

        System.out.printf("Сума їх потужностей = %d к.с.\n Сума їх об'ємів = %.2fл",sumpower, sumvolume);
    }
}

Завдання 5
public class Fifth {
    public static void main(String args[]) {
        int number = 822;

        int firstNum = number/100;

        int secondNum = number%100/10;

        int thirdNum = number%10;

        System.out.printf("%d%d%d",thirdNum,secondNum,firstNum);
    }
}
