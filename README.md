# nthtribo

*/
class Solution {
  public int tribonacci(int n) {

    final int[] sequence = {0, 1, 1};

    for(int i = 3; i <= n; ++i) {
      sequence[i % 3] = sequence[0] + sequence[1] + sequence[2];
    }

    return sequence[n % 3];
  }
}

Source: https://leetcode.com/problems/subtract-the-product-and-sum-of-digits-of-an-integer/
Time: O(n), where n is the given number
Space: O(1), in-place
*/

class Solution {
  public int subtractProductAndSum(int n) {

    int product = 1;
    int sum = 0;

    while(n != 0) {
      int digit = n % 10;
      product *= digit;
      sum += digit;
      n /= 10;
    }

    return product - sum;
  }
}
