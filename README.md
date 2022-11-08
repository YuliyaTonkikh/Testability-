# Решение
public class BonusMilesService {

    public int calculate (int cost) {
        int result = (cost / 20);
        return result;
    }
}


public class Main {
    public static void main(String[] args) {
        BonusMilesService service = new BonusMilesService();
        int prise = 10000;
        int miles = service.calculate(prise);
        System.out.println(miles);
    }
}