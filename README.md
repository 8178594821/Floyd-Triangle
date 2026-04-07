# Floyd-Triangle
The main idea behind Floyd’s Triangle is to use nested loops. The outer loop controls the number of rows, while the inner loop is responsible for printing numbers in each row. A separate variable is used to keep track of the current number, which increments after every print.

class Solution {
    public void printFloydTriangle(int n) {
        
        int num = 1;
        
        for(int i = 1; i <= n; i++){     
            for(int j = 1; j <= i; j++){
                System.out.print(num + " ");
                num++;
            }
            System.out.println();
        }
    }
}
