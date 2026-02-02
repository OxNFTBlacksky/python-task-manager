# python-task-manager
A lightweight task management tool to practice Python basics and clean code.
def main():
    tasks = []
    while True:
        print("\n--- Simple To-Do List ---")
        print("1. Add Task")
        print("2. Show Tasks")
        print("3. Exit")
        choice = input("Choose an option: ")

        if choice == '1':
            task = input("Enter the task: ")
            tasks.append(task)
            print("Task added!")
        elif choice == '2':
            print("\nYour Tasks:")
            for i, t in enumerate(tasks, 1):
                print(f"{i}. {t}")
        elif choice == '3':
            break
        else:
            print("Invalid choice, try again.")

if __name__ == "__main__":
    main()
    # Simple To-Do App
This is a basic CLI-based To-Do List application written in **Python**.

## How to run
1. Make sure you have Python installed.
2. Run the command: `python todo.py`
3. 
