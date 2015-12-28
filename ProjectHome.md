## What ##
VBClass is a cross browser function able to define VBScript like classes via JavaScript.

## Where ##
All Internet Explorer version I could test, included 5.5, 6, 7, 8, plus all ES5 ready browsers, plus all browsers with defineGetter and defineSetter support.

## Why ##
Getters and Setters are semantically perfect and totally transparent for users. We may choose some convention that pretends to simulate them or we can use full support through a proper class definition where methods are immutable and properties must have been defined in advance. VBClass brings a robust way to create objects that follows stricter rules, object that could be used whenever we would like to add getters and setters power in our framework, library, application.