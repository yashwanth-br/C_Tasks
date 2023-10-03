# 1. Write a C program to find the letter in a String given by the user and display the index of first occurrence of it.

## Example Output 1

```bash
Enter the String: Vidyavardhaka
Enter the letter to be found: v
Index of first occurrence: 5
```

Note: In the above example, Though letter 'v' is 6th letter in the String, it's index is 5. If you still have any doubts you may contact us for clarification.

Note 2: Remember, C language is case sensitive. Capital and small letters are treated as different characters, so in the above example as we have given small 'v' to find, it did not consider the first letter which is a Capital 'V'.

## Example Output 2

```bash
Enter the String: Engineering
Enter the letter to be found: t
Letter not found in the String!
```


# 2. Find the number of occurrence of a letter in a given String.

## Example Output 1

```bash
Enter the String: Vidyavardhaka
Enter the letter to be found: a
Number of occurrence of 'a' is 4 
```
## Example Output 2

```bash
Enter the String: Engineering
Enter the letter: h
Letter not found in the String!
```

# 3. Replace the letter in the given String.

## Example Output 1

```bash
Enter the String: EngineeRing
Enter the index to be replaced: 7
Enter the letter: r
Replaced 'R' with 'r'!
The Final String is "Engineering"
```
Note: Remember, C language is case sensitive. Capital and small letters are treated as different characters, so in the above example Captial 'R' got successfully replaced with small 'r'.
## Example Output 2

```bash
Enter the String: Vidyavardhaka
Enter the index to be replaced: 5
Enter the letter: v
Characters are same, Nothing got replaced!
The Final String is "Vidyavardhaka"
```
Note: As the 5 index in the string was already the character to be replaced (i.e. 'v'), the string was untouched.

# 4. Find the length of a given string without using strlen function.

## Example Output 1

```bash
Enter the String: Engineering
The length of the string is 11
```
## Example Output 2

```bash
Enter the String: Vidyavardhaka
The length of the string is 13
```

# 5. Copy a string to another string without using strcpy function.

## Example Output

```bash
Enter the String 1: Apple
Enter the String 2: Orange
String 1: Orange
String 2: Orange
```
Note: Here don't just print the string as it is, you need to copy the string from string 2 to string 1 and then print the contents of string 1 and string 2.
