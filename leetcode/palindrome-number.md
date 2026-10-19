# Palindrome Number

```java
class Solution {
    public boolean isPalindrome(int x) {
        if (x < 0) {
            return false;
        }

        int reverseX = 0;
        int originalX = x;
        while (x != 0) {
            reverseX = reverseX * 10 + (x % 10);
            x = x / 10;
        }

        return reverseX == originalX;
    }
}
```