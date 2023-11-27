# Stream API Exercise: Reverse Words

## Task Description
Write a function that takes a string with one or more words, and returns the string with words of five or more letters reversed. The input strings should consist only of letters and spaces. Spaces will be included only when more than one word is present.

### Examples:
- `spinWords("Hey fellow warriors")` => returns "Hey wollef sroirraw"
- `spinWords("This is a test")` => returns "This is a test"
- `spinWords("This is another test")` => returns "This is rehtona test"

## Implementation
The `spinWords` function should take a string as input and return the modified string as specified in the task description.

```java
public class SpinWords {

    /**
     * Reverse words of five or more letters in a given string.
     *
     * @param input The input string containing words to be reversed.
     * @return The modified string with reversed words.
     */
    public static String spinWords(String input) {
        // Implement the logic to reverse words with five or more letters
        // and return the modified string.
        // ...

        return modifiedString;
    }

    public static void main(String[] args) {
        // Example usage of the spinWords function
        System.out.println(spinWords("Hey fellow warriors")); // "Hey wollef sroirraw"
        System.out.println(spinWords("This is a test")); // "This is a test"
        System.out.println(spinWords("This is another test")); // "This is rehtona test"
    }
}
```

## Running the Code
Test the functionality of the `spinWords` function by calling it with different input strings in the `main` method.

## Additional Notes
- Ensure correct handling of cases where words are separated by spaces.
- Pay attention to edge cases, such as an empty string or strings with no words of five or more letters.
