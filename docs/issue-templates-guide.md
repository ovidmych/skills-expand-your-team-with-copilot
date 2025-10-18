# Issue Templates Guide for Teachers

This repository includes several issue templates designed to make it easy for teachers to request changes without needing to understand the technical details of the application.

## Available Templates

### 1. Add New Activity
**Use this when:** You want to add a brand new extracurricular activity to the system.

**What you'll provide:**
- Activity name
- Description
- Schedule (days and times)
- Maximum number of participants
- Any additional information

**Example use case:** Adding a new "Robotics Club" that meets on Wednesdays from 3:30-5:00 PM.

### 2. Modify Activity Details
**Use this when:** You need to change information about an existing activity (schedule, description, or participant limit).

**What you'll provide:**
- Which activity to modify
- What needs to change (description, schedule, max participants, or name)
- The new information
- Reason for the change

**Example use case:** Changing Chess Club's meeting time from 3:15 PM to 4:00 PM due to room availability.

### 3. Bug Report
**Use this when:** Something isn't working correctly in the system.

**What you'll provide:**
- Clear description of the problem
- Steps to reproduce the bug
- What should happen vs. what actually happens
- Any error messages you see

**Example use case:** Students can't sign up for Basketball Team - an error appears when clicking the signup button.

### 4. Feature Request
**Use this when:** You have an idea for a new capability or improvement.

**What you'll provide:**
- Description of the new feature
- The problem it solves
- Priority level
- How you envision it working

**Example use case:** Add ability to export a list of all students enrolled in each activity to a spreadsheet.

### 5. UI/UX Improvement
**Use this when:** The interface is confusing, hard to use, or could look better.

**What you'll provide:**
- Which page or area needs improvement
- Current experience vs. desired experience
- Type of improvement needed
- Who is affected (students, teachers, or both)

**Example use case:** Make the activities list easier to read by adding visual cards instead of a plain list.

### 6. Data Management
**Use this when:** You need to manage student enrollments or participant lists.

**What you'll provide:**
- Type of data request (remove student, bulk enroll, etc.)
- Activity name
- Student email addresses
- Reason for the request

**Example use case:** Remove a student from Soccer Team because they transferred to another school.

## How to Create an Issue

1. Go to the [Issues tab](../../issues) in this repository
2. Click the green "New issue" button
3. Select the appropriate template from the list
4. Fill out all required fields (marked with red asterisks)
5. Add any optional information that might be helpful
6. Click "Submit new issue"

## What Happens Next

Once you submit an issue:
1. Your issue will be reviewed and assigned automatically or by a team member
2. GitHub Copilot coding agent may be assigned to implement straightforward requests
3. The issue includes all the context needed for implementation
4. You'll be notified of progress and can comment with any questions
5. When complete, the issue will be closed and changes will be ready to test

## Tips for Writing Good Issues

### Be Specific
❌ Bad: "Chess Club needs changes"  
✅ Good: "Change Chess Club meeting time from 3:15 PM to 4:00 PM due to room conflict"

### Include All Required Information
All templates have required fields. Make sure to fill them all out completely.

### Use Real Examples
If requesting a new feature, describe a real scenario where you'd use it.

### Add Context
Explain WHY you need the change, not just WHAT change you need.

### Be Patient
Some changes are quick, others take more time. Check back on your issue for updates.

## Need Help?

- **Documentation**: Check the [Development Guide](../docs/how-to-develop.md) for technical information
- **GitHub Copilot**: Learn more about [GitHub Copilot](https://docs.github.com/en/copilot) features
- **Questions**: You can still create a blank issue if none of the templates fit your needs

## Template Structure

Each template includes:
- **Clear problem description**: Structured fields to describe what you need
- **Clear acceptance criteria**: How we'll know when the task is complete
- **Hints, tips, and suggested solutions**: Guidance for the developer implementing the change
- **Limitations and context**: Related information to help with implementation

This structure ensures that GitHub Copilot coding agent or human developers have everything they need to implement your request without needing to ask for clarification.
