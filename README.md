🌳 BST Visualization Program - Student Grade Management

This C++ program provides a way to manage and visualize student data using a Binary Search Tree (BST). The BST structure is ideal for maintaining sorted student records, enabling efficient operations such as insertion, searching, updating, and deletion. This program is particularly useful for visualizing how data is organized in a BST based on student grades.
🛠️ Core Features:

    Node Representation (tnode class):
        Each node in the BST stores a student's information, including:
            regno (Registration Number): A unique identifier for each student.
            name (Student Name): The student's name.
            course (Course Name): The course the student is enrolled in.
            grade (Grade): The student's grade, which determines the node's position in the BST.
        The node also contains pointers to its left and right children (left, right), representing the left and right subtrees.

    BST Operations (studentgradechecker class):
        Insertion (insert): Adds a new student to the tree based on their grade. Students with lower grades are placed on the left, and those with higher grades on the right.
        Traversal Methods:
            Inorder (displayinorder): Displays the students sorted by their grades (ascending order).
            Preorder (displaypreorder): Displays the students starting from the root, followed by the left and right subtrees.
            Postorder (displaypostorder): Displays the students after visiting both subtrees and the root.
        Search (search): Locates a student in the BST based on their registration number.
        Update (update): Modifies a student's grade.
        Delete (remove): Removes a student from the tree, ensuring the BST property is maintained.
        Find Max/Min Grade (maxgrade/mingrade): Identifies the student with the highest or lowest grade.
        Tree Height Calculation (getheight): Computes the height of the tree, giving an idea of its balance and depth.

    📁 File Handling:
        The program reads student data from a file (data.txt), automatically populating the BST with the records. This makes it easy to initialize the tree with pre-existing data.

    🖥️ User Interaction (in main):
        The user can interact with the program through a menu-driven interface. They can choose to display, search, update, or delete records, or find the student with the highest or lowest grade.

🎓 Educational Value:

This program not only serves as a practical application of BSTs but also helps in understanding how data structures like trees can be used to organize and manage data efficiently. The visualization aspect, where students' data is arranged and manipulated in a tree structure, provides a clear and intuitive way to learn about the properties and operations of BSTs.
