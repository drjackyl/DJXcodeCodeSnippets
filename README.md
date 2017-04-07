# DJXcodeCodeSnippets

Xcode code-snippets for Swift-projects

## How to use these snippets

The user's code-snippets in Xcode are located in

```
~/Library/Developer/Xcode/UserData/CodeSnippets
```

If you did not create your own code-snippets, yet and don't plan to do so, you can simply clone this repository to the pathmentioned above.

If you have your own snippets and want to add these, I suggest to clone these to any location and copy them to your snippets-folder.

## List of snippets

### Documentation Markup

When adding the comment for documentation markup, Xcode behaves very inconveniently, by not indenting correctly. So I added a snippet to just start that comment:

```swift
/**
 <#text#>
 */
```

With that snippet - magic, magic - Xcode gets the indentation done right immediately.


### Documentation Markup: Callouts

The documentation-markup supported by Xcode provides a list of callouts for symbol-documentation and Playgrounds. The documentation then becomes visible, when opening the Quick-Help-popup by Alt-clicking. The callouts only supported by Playgrounds are rendered in a special way, when choosing to show the rendered markup within the playground. Currently, the following callouts are included:

Attention, Author, Authors, Bug, Complexity, Copyright, Custom (Playground only), Date, Example (Playground only), Experiment, Important, Invariant, Note, Parameter, Parameters, Postcondition, Precondition, Remark, Requires, Returns, SeeAlso, Since, Throws, ToDo, Version, Warning
