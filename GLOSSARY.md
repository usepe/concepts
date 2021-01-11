# Glosary

## B

#### <a href="#boy-scout-rule"></a>Boy-scout Rule

See [Litter-Pickup Refactoring](#litter-pickup-refactoring)

## C

#### <a href="#comprehension-refactoring"></a>Comprehension Refactoring

Similar to [Litter-Pickup Refactoring](#litter-pickup-refactoring). Both require a refactoring, but one comes from smelly code, the other is coming from need to comprehension.

## D

#### <a href="#design-stamina-hypothesis"></a>Design Stamina Hypothesis

The longer you keep not paying atention to your design on your system, the longer it will take to make changes on it.

#### <a href="#dependency-inversion-principle"></a>Dependency Inversion Principle

Is a design principle part of [SOLID](#solid). States that one should make it code depend on abstractions and not implementations. With this you can ensure you can change the underlaying implementation meanwhile it behaves in the same way as the abstraction meant it should work.

#### <a href="#domain-driven-design></a>Domain Driven Design

.

## I

#### <a href="#interface-segregation-principle"></a>Interface Segregation Principle

Is a design principle part of [SOLID](#solid). States that a client should only know the parts it needs to work. That  means that is better to have little and more specific interfaces instead of a larger one with information that may not be needed.

## L

#### <a href="#litter-pickup-refactoring"></a>Litter-Pickup Refactoring

Always leave the code better than when you found it rule (a.k.a **boy-scout rule**)

Perform minor refactoring on code that you are working on to find it better the next time you have to dive into it.

#### <a href="#liskov-substitution-principle"></a>Liskov Substitution  Principle

Is a design principle part of [SOLID](#solid). States that any implementation of a class should be able to be changed by another implementation of the same type. In other words if the unit of code has the same interface implemented you should be able to interchange it without worrying about implementation details.

#### <a href="#long-term-refactoring"></a>Long-Term Refactoring

Kind of a planned refactoring, but that uses the other approaches to break down with a long-term plan in place.

The best of it is that let you pivot if needed, and learn from each gradual step.

## O

#### <a href="#open-closed-principle"></a> Open/Closed Principle

Is a design principle part of [SOLID](#solid). States that all classes (or any single unit of code) should be open for extension but closed from modification. In other words, once accepted a contract with the outside, that contract should remain unchanged if a new feature/improvement is needed.

## P

#### <a href="#planned-refactoring"></a> Planned Refactoring

Refactoring that takes place on code that was leaved unmantained, or without applying refactoring, for long period of times and is included in the agenda of changes as "Need to refactor this".

It is a good advice to not do this kind of refactorings unless they cannot be avoided, as they are hard to justify.

#### <a href="#preparatory-refactoring"></a> Preparatory Refactoring

Refactoring that takes place to add a new feature when the existent code base is not a good fit.

## S

#### <a href="#single-responsibility-principle"></a> Single Responsibility Principle

Is a design principle part of [SOLID](#solid). States that a class (or any single unit of code) should have only one responsibility and therefore only one reason to change.

#### <a href="#solid"></a>SOLID

Acronim coined by Robert C. Martin (a.k.a. Uncle Bob). Each of those letters represent a basic principle of object oriented programming and design. Those principles stand as guidelines to write systems that can be extended and maintained over time.


## U

#### <a href="#ubiquitous-language"></a> Ubiquitous Language

A language structured around the domain model and used by all team members to connect all the activities of the team with the software, within a bounded context.


See:
- [Single Responsibility Principle](#single-responsibility-principle)
- [Open/Closed Principle](#open-closed-principle)
- [Liskov Substitution Principle](#liskov-substitution-principle)
- [Interface Segregation Principle](#interface-segregation-principle)
- [Dependency Inversion Principle](#dependency-inversion-principle)
