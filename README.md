# DevCamp Android Homework Repository

Welcome! This repo uses multiple product flavors to isolate each student's homework work.

## Project Setup

- Flavors are based on two dimensions:  
  - **name** (students: Bobby, Geri, Kiro, Miro, Svetlio, Boyan)  
  - **homework** (e.g. homework1)  
- Example combined flavor: `BobbyHomework1`  
- Each flavor corresponds to a source folder: 
- Shared code/resources live in `app/src/main/`.

## How to Work

1. **Select your flavor** in Android Studio via the Build Variants panel (e.g., `BobbyHomework1`).
2. **Work only inside your flavor folder** (`app/src/<YourFlavorName>/`).
3. **Create and use your own git branch**, e.g., `bobby/homework1`.
4. Commit your changes **only to your branch**, never directly to `main`.
5. When ready, **open a Pull Request** from your branch to `main` with a clear title like: (e.g., `Homework 1 Bobby`)
6. Use descriptive commit messages (e.g., `Added HomeScreen setup`, `Added ui component for`)

## Why This Setup?

- Keeps everyone’s work isolated to avoid conflicts.
- Makes it easy to review and merge individual homework.
- Lets you switch flavors easily inside Android Studio.

Thanks for contributing and happy coding! 🚀

