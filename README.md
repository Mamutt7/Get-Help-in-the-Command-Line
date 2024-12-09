# Get-help-in-the-Linux-Command-Line

## Activity overview
As a security analyst, you won’t have all the answers all the time, but you can learn where to find them. One of the great things about Linux is that you can get help right through the command line.

In this lab activity, you’ll use the `man` and `whatis` commands to get information on other commands and how they work. You’ll also use the apropos command to search the manual page for a command with a specified string.

When working as a security analyst, you'll likely find it useful to know how to discover which command to use or information about what commands do.

With that in mind, let’s explore your scenario.

## Scenario
In this scenario, you have to find more information about commands that you need to use. You also need to discover which command to use to perform a certain task.

Here’s how you’ll do this task: First, you’ll explore a few commands you can use in the shell to learn more about other commands. Next, you’ll find an option you need to add to a command. Third, you’ll use a command to get a brief description of commands so you can identify their differences. Finally, you’ll identify the command you need to perform a task.

It's time to get ready to explore some of the Linux help resources!

### Task 1. Learn more about commands
In this task, you need to explore a few commands you can use in the shell to learn more about the functionality of other commands.

First, imagine you can’t quite remember what the `cat` command does and want a quick reminder.

1. Run the `whatis` command to get a short description of `cat`.

Next, imagine that you want more details about `cat` and all of its options.

2. Use the `man` command to get more details about `cat`.

![image](https://github.com/user-attachments/assets/f92293c5-8d2b-465f-b230-1584a417be67)

When the first page of information returned by man is displayed, the output pauses.

3. Press Q to exit this manual page.

Now, imagine you’ve remembered there’s a command that prints just the first part of a file, but you can’t remember the exact command. The `apropos` command is useful in these instances. You can use keywords with `apropos` to find a command.

4. Use `apropos` to find a command that returns the first part of a file:

```
apropos -a first part file
```

![image](https://github.com/user-attachments/assets/f6a29e5e-bf46-4923-a13f-6243796bc16a)


### Task 2. Explore the useradd command
In this task, imagine that you want to set the expiration date for a temporary user account. You know that you need to use the useradd command for this, but you’re not quite sure how to complete the task. You realize it might involve adding an option to the command.

1. Use the most appropriate Linux command to get help on the `useradd` command and learn more about all of its options.

2. Press Q to exit this manual page.

![image](https://github.com/user-attachments/assets/1f391eaf-a270-4472-8629-ee1110fb7bfe)


### Task 3. Explore the rm and rmdir commands
In this task, you need to determine the difference between the rm and rmdir commands.

Imagine that you’ve used these commands before, but you can’t remember how they’re different.

- Use the most appropriate Linux command to quickly remind yourself what each command does.

![image](https://github.com/user-attachments/assets/8c6e2191-b81e-4016-96a9-532e88df5457)


### Task 4. Determine which command to use
In this task, imagine that you need to create a new group but you can’t remember what command to use. You need to identify a command that will do this by searching for it through keywords. In this case, use the keywords create new group.

- Use the most appropriate Linux command with these keywords to identify what command to use.

![image](https://github.com/user-attachments/assets/58b4461d-3cad-421c-a11a-b07db778c54e)
