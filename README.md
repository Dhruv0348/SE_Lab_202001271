# SE_Lab_202001271

# Library Information System (LIS)
## Identifying Functional and Non-Functional Requirements

### Q1: Identification of Functional and Non-Functional Requirements

### Functional Requirements:

###
1. All the necessary details about the book should be displayed on the system.
2. Users should be able to search for books in te library using various criteria, such as title, author, and publication date.
3. Users should be able to borrow or return books only if they are members of the system.
4. Before issuing a book, the system should ask for a username and password.
5. Librarians should acknowledge the borrower's request and acknowledge the loan process.
6. The system should allow librarians to add or remove records for new or removed books.
7. A user should be shown that the book is unavailable instead of the option to borrow if the book is already borrowed.
8. Location of the borrowed book should be shown by the system in the library.
9. Notification of overdue books should be sent to the user and the librarian along with calculation of fines for late returns.
10. A list of a user's current and past borrowings should be displayed including the date of borrowing and returning if requested.

### Non-Functional Requirements:

###
1. Performance => The system should respond within 2-3 seconds upon request.
2. Accuracy => Accurate information about the book and fines should be stored and displayed by the system.
3. Scalability => Even with a large number of users, the system should work reliably.
4. Maintainability => The system shold work porperly after changes and should be easy to upadte.
5. Security => The system should eb secure on the institute's LAN and should prompt for a username and password.
6. Portability => Accessibilty of the system from any system should be ensured.
7. Flexibility => A user-friendly interface with language options should provide relevant information easily.

### Q2: Scope and Requirements for Deaf Communication Application

### Scope:
- The problem identified is to address the needs of individuals who have disabling hearing loss. According to the statement, 5% of the world population, or approximately 466 million people, suffer from this condition.
- The solution proposed is to develop a mobile application that uses artificial intelligence to recognize key sound events that are important to this community, such as car horns and crying babies.

- The app is designed to provide immediate alerts for these sound events, which can be critical for the user, and to log the events for future reference. The app is optimized for Android devices and is designed to have low latency so that it works in real-time.
- The goal is to create an impactful solution for individuals with disabling hearing loss that addresses some of their everyday needs.

### Functional Requirements:

###
- Users should be allowed to choose an alert tone such as a bell or radar sound for immediate notifications by the system.
- Ability to choose the output type, either as a tone, vibration, or both.
- Ability to edit or delete voice information types.
- Functionality to choose multiple voice requirements for voice recognition.
- Flexibility to choose where to send the alert, either by telephone, email, or both.

### Non-Functional Requirements:

###
- Performance: It is critical for the application to have low-latency real-time operation be effective.
- Capacity and Scalability: The mobile application should be scalable in case of an increase the user base.
- Usability: The application should be easy to use for people with hearing loss.
- Reliability: The application should be reliable and provide consistent performance.
- Security: The application should protect the privacy and sensitive information of users.
- Disaster Recovery: The system and server should not experience any down time at all as it is cruicial for the ill to be able to use the application at all the times. For this, alternative deployments can be made and multiple servers in different regions can be used.
