# Gym-Management-System
Here's a GitHub-friendly `README.md` file for your Gym Management System:

---

# Gym Management System 🏋️‍♂️

A simple C++ program that manages gym memberships, tracks attendance, and calculates total fees.

## Features ✨
- **Add Members**: Store member details (name and age).
- **Mark Attendance**: Track whether a member attended the gym.
- **Calculate Fees**: Compute total fees based on attendance and age:
  - Members **above 20 years old** pay **200** per session.
  - Members **20 years old or younger** pay **100** per session.

## Technologies Used 🛠️
- C++
- Object-Oriented Programming (OOP)
- `vector` for managing members

## How to Run 🏃‍♂️
1. **Compile the Code**:
   ```
   g++ gym.cpp -o gym
   ```
2. **Run the Program**:
   ```
   ./gym
   ```
3. **Use the Menu** to manage gym members.

## Example Usage 📌
```
***** Gym Management *****
1. for add member:
2. for mark attendance:
3. for Total fees:
0. for exit:
Enter choice: 1
Enter name: John
Enter age: 25
Member Added

Enter choice: 2
Enter name: John
Attendance marked for member: John

Enter choice: 3
Total Fees: 200
```

## Future Enhancements 🚀
- Implement a **database or file system** for persistent storage.
- Allow **multiple attendance records** per member.
- Add **membership plans** with different pricing.

## Contributing 🤝
Feel free to contribute! Fork the repository, make changes, and submit a pull request.

## License 📜
This project is open-source and free to use.
