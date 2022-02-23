# verou-3-hoe-om-vragen-Cloesick
# How to ask questions

Drafting a guide on how to ask a good question.

## Background story

You are working on the OOP concepts. You try tp understand the private, protected and public access modifiers. You are stuck because you don't know when or why you should use them. What do you do now?

### Step 1 - Understand your problem

- Start by being veeery friendly
- Explain what you are trying to achive/your situation
- Describe what you already have  
- Describe where things go wrong
- Explain what you already have tried to solve the problem
- Explain the steps you took to get to the result

Story: You have a function calculateSalary() and you have a formula in that function which calculates your employers' salary. You don't want anyone else without rights to modify it (only admins).

### Step 2 - Show your code and explain where it goes wrong

Correctly show all your code in the language you are writing. Add relevant tags to your question (e.g.: php, oop, access modifiers, ...). Explain where in your code things go wrong by using comments to show exact location/line.

```php
class Main 
{
    $employer = new Employer();
    calculateSalary($employer);
}

class Employer 
{
    public __construct() {}

    public function calculateSalary(Employer employer) {
        return employer->salary * 5; // things go wrong here
    }
}
```

### Step 3 - Tell what you have tried

Explain the possible solutions you tried and try to show code snippets.

### Step 4 - Ask nicely for help and show gratitude
