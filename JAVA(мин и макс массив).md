# package less1;

public class less3 {
    public static void main(String[] args) {
        int arr[] = {12,435,567,768};
        int min = 0;
        int max = 0;
        for (int i = 0; i < arr.length; i++) {
            if (arr[i] > max) {
                max = arr[i];
            }
            min = max;
        }
        for (int j = 0; j < arr.length; j++) {
            if (arr[j]<min) {
                min = arr[j];
            }
        }
        System.out.println("Мин:" + min);
        System.out.println("Макс:" + max);
    }
}
