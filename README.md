# haccerank-2darray-
import java.util.ArrayList;
import java.util.List;
public class Tester {
   public static void main(String[] args) {
      List<int[]> rows = new ArrayList<>();
      rows.add(new int[]{1,2,3});
      rows.add(new int[]{1,2});
      rows.add(new int[]{1});
      //get element at row : 0, column : 0
      System.out.println("[0][0] : " + rows.get(0)[0]);
      //get element at row : 1, column : 1
     System.out.println("[1][1] : " + rows.get(1)[1]);
   }
}
