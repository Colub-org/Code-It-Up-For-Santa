# 
Challenge 1: Present Counter

**Objective:**
Participants are tasked with creating a program to help Santa count the number of presents he needs to deliver. Given a list of different types of gifts, participants should write a program that counts the quantity of each type of gift and provides a total count.

**Instructions:**
1. **Input:**
- Participants will be given a predefined list of gifts, where each gift is represented by a string.
- Example: ["Toy", "Candy Cane", "Doll", "Toy", "Candy Cane", "Teddy Bear"]

2. **Output:**
- The program should output a summary, displaying each type of gift and the quantity of that gift.
- Example Output:
```
Gift Summary:
- Toy: 2
- Candy Cane: 2
- Doll: 1
- Teddy Bear: 1
```

3. **Counting Logic:**
- Participants need to implement logic to iterate through the list and count the occurrences of each type of gift.
- They should use appropriate data structures (e.g., dictionaries, arrays) to store and manage the counts.

4. **Challenge Details:**
- The number of gifts in the provided list will vary, and participants should create a dynamic solution that works for any list of gifts.
- Encourage participants to consider edge cases, such as an empty gift list.

5. **Tips:**
- Participants can use loops (e.g., for or while) to iterate through the gift list.
- Consider providing hints about using dictionaries to store gift counts, with gift names as keys and counts as values.

Example of code should look this way. This is just a skeleton or wireframe, and elfs are meant to come up with 15 gifts for Santa.
```py
def count_presents(gift_list):
  gift_counts = {}
  # Iterate through the gift list and update counts
  for gift in gift_list:
  # Logic to update counts in the dictionary
  # ...

  # Print the summary
  print("Gift Summary:")
  for gift, count in gift_counts.items():
    print(f"- {gift}: {count}")

# Example usage
gifts_to_deliver = ["Toy", "Candy Cane", "Doll", "Toy", "Candy Cane", "Teddy Bear"]
count_presents(gifts_to_deliver)```
