# nthtribo........
~......... solution with......
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

------END-------

Source: https://leetcode.com/problems/subtract-the-product-and-sum-of-digits-of-an-integer/
Time: O(n), where n is the given number
Space: O(1), in-place
*/

class Solution {
  public int subtractProductAndSum(int n) {

    int product = 1;
    int sum = 0;
.

    while(n != 0) {
      int digit = n % 10;
      product *= digit;
      sum += digit;
      n /= 10;
    }.

    return product - sum;
  }
}
--------------------END--------------------
/*
Source: https://leetcode.com/problems/count-of-matches-in-tournament/
Time: O(1)
Space: O(1), in-place
*/

class Solution {
  public int numberOfMatches(int n) {

    return n - 1;
  }
}

/*
Source: https://leetcode.com/problems/count-of-matches-in-tournament/
Time: O(1)
Space: O(1), in-place
*/.

class Solution {
  public int numberOfMatches(int n) {

    return n - 1;
  }
}

/*
Source: https://leetcode.com/problems/reverse-integer/
Time: O(log base10 n), where n is the given integer(x)
Space: O(1), in-place
*/

class Solution {
public:
  int reverse(int x) {

    const int maxValByTen = INT_MAX / 10;
    const int minValByTen = INT_MIN / 10;
    int rev = 0;

    while(x != 0) {

      if(rev > maxValByTen || rev < minValByTen) {
        return 0;
      }

      rev = (rev * 10) + (x % 10);
      x /= 10;
    }

    return rev;

  }
};

al int[] sequence = {0, 1, 1};

    for(int i = 3; i <= n; ++i) {
      sequence[i % 3] = sequence[0] + sequence[1] + sequence[2];
    }

    return sequence[n % 3];
  }
}



Source: https://leetcode.com/problems/count-of-matches-in-tournament/
Time: O(1)
Space: O(1), in-place
*/

class Solution {
public:
  int numberOfMatches(int n) {

    return n - 1;
  }
Source: https://leetcode.com/problems/count-of-matches-in-tournament/
Time: O(1)
Space: O(1), in-place
*/

class Solution {
public:
  int numberOfMatches(int n) {

    return n - 1;
  }


/*
Source: https://leetcode.com/problems/count-of-matches-in-tournament/
Time: O(1)
Space: O(1), in-place
*/

class Solution {
public:
  int numberOfMatches(int n) {

    return n - 1;
  }
};
Source: https://leetcode.com/problems/find-peak-element
Time: O(log base2 n), where n is the size of the array and (log base2 n) is the maximum number of possible iterations
Space: O(1), in-place
*/

class Solution {
public:
  int findPeakElement(vector<int>& nums) {

    int start = 0;
    int end = nums.size() - 1;

    while(start < end) {

      int mid = start + ((end - start ) >> 1);
      int nextIndex = mid + 1;

      if(nums[mid] < nums[nextIndex]) {
        start = nextIndex;
      }else {
        end = mid;
      }
    }

    return start;
  }
};
                                     
                                     /*
Source: https://leetcode.com/problems/isomorphic-strings/
Time: O(n), where n is the length of the given string(s)
Space: O(1), in-place
*/

class Solution {
  public boolean isIsomorphic(String s, String t) {

    char[] sCharMaps = new char[256];
    boolean[] isMapPresent = new boolean[256];
    int len = s.length();

    for(int i = 0; i < len; ++i) {

      char sChar = s.charAt(i);
      char tChar = t.charAt(i);
      char sCharMap = sCharMaps[sChar];

      if(sCharMap != 0) {
        if(sCharMap != tChar) {
          return false;
        }
      } else if(isMapPresent[tChar]) {
        return false;
      } else {
        sCharMaps[sChar] = tChar;
        isMapPresent[tChar] = true;
      }
    }

    return true;
  }
}

Source: https://leetcode.com/problems/subtract-the-product-and-sum-of-digits-of-an-integer/
Time: O(n), where n is the given number
Space: O(1), in-place
*/

class Solution {
public:
  int subtractProductAndSum(int n) {

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
};

class Solution {
public:
  int subtractProductAndSum(int n) {

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
};

class Solution {
public:
  int subtractProductAndSum(int n) {

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
};

class Solution { public int subtractProductAndSum(int n) {

int product = 1;
int sum = 0;

while(n != 0) {
  int digit = n % 10;
  product *= digit;
  sum += digit;
  n /= 10;
}

return product - sum;
} } --------

class Solution { public int subtractProductAndSum(int n) {

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


class Solution { public int subtractProductAndSum(int n) {

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


class Solution { public int subtractProductAndSum(int n) {

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
class Solution { public int subtractProductAndSum(int n) {

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

class Solution { public int subtractProductAndSum(int n) {

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
-------------

********************
