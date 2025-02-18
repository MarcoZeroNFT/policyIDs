# policyIDs
CNFTs Verified Policy Database 

__**To add your project to the list of verified policies for the marketplace:**__

**__Important:__ You must show proof of your project by tweeting your pull request to your projects twitter and linking in your pull request
Alternatively, provide adequate proof such as a direct link to project website with policies**

Make a pull request to add a file in the "projects" directory of this repository in the following format.
Please note that the name of the file **must not** contain any special character (:,./\@"').

__**Information:**__

**project:** Name of your project

**policies** one or many policy ids of your project

https://youtu.be/8hoYS1xCyWM

Validate your code before requesting: https://jsonformatter.curiousconcept.com/#

Single Project:
```json
[
  {
    "project": "YourFirstProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  }
]

```

Multiple Projects under one name:
```json
[
  {
    "project": "YourFirstProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  },
  {
    "project": "YourSecondProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  },
]
```
