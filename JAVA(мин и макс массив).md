package less1;

public class num5 {
    public static void main(String[] args) {
        int[] arr = {2,4,6,3,4,8};
        boolean rez = true;
        one(arr,rez);

    }


    public static void one(int[] arr,boolean rez) {
            int sum1 = arr[0] + arr[1] + arr[2];
            int sum2 = arr[3] + arr[4] + arr[5];
        System.out.println("Сумма первых 3:"+sum1);
        System.out.println("Сумма вторых 3:"+sum2);
            if(sum1 != sum2){
                rez = false;}
            else {
                rez = true;}
        System.out.println("Результат:  "+rez);


    }
}
