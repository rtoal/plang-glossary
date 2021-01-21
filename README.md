# The Programming Languages and Compilers Glossary

### Abstract Class
A class that is not allowed to have any instances (it is intended to be subclassed).

### Abstract Method
A method of an abstract class or interface that has no implementation.

### Abstract Syntax
A representation of a program’s structure without low-level details such as punctuation and preposition-like keywords that serve only to impose a structure on linear program text.

### Activation Record
See [Frame](#frame).

### Actor
A concurrent process that communicates by sending and receiving messages.

### Agent
An entity that acts on behalf of another entity.

### Alias
One of the names of a multiply-named entity.

## Aliased
An entity to which multiple names are bound.

### Annotation
A form of metadata attached to an entity.

### AOT
(1) Method of language translation in which the source language is translated fully _before_ interpretation, that is, **A**head-**O**f-**T**ime. (2) English abbreviation for the manga 進撃の巨人.

### Argument
An expression passed to a (parameterized) entity during a call, instantiation, or other invocation.

### Assignable
A mutable storage location. Used in place of the term **variable** when emphasizing mutability.

### Assignment
A run-time association of a _value_ with a (mutable) variable.

### Asynchronous
A type of invocation in which the caller does not wait for the callee to complete.

### Atom
A named primitive entity whose value is, essentially, itself. Also known as a #symbol.

### Atomic Object
An object that can be operated upon safely in a multithreaded environment without _explicit_ synchronization code. Often the object holds a numeric value on which “compound” operations such as compare-and-set or get-and-add can be done atomically.

### Automatic Reference Counting (ARC)
A mechanism in which the compiler inserts code to release and retain blocks of memory so the programmer does not have to, specifically by counting the number of active references to the block and freeing the block when the reference count becomes zero.

### Billion-Dollar Mistake
The implicit extension of types to include a null value. For example, Java is said to suffer from the billion-dollar mistake since `null` is essentially a member of the `String` type; Swift does not since the types `String` and `String?` are distinct.

### Binding
An association of a _name_ with an entity (which can occur at compile-time or run-time).

### Borrow
The use of a resource without taking full ownership.

### Callback
A function _f_ both passed to a function _g_ and invoked within the body of _g_.

### Character
(1) A named, abstract symbol. (2) The type of characters.

### Class
An entity from which objects are created. Objects instantiated from a class have the structure and behavior defined by the class, though in some languages instances are allowed to be customized.

### Class Variable
A property that belongs to a class, rather than to the instances of the class. Sometimes known as a **static field** or **static property**.

### Closure
A block or function with free variables that get their values from the environment in which the block or function is defined.

### Code Point
The unique, nonnegative integer value assigned to a character in a character set.

### Coercion
An implicitly applied type conversion.

### Comprehension
A composite value defined by means of an expression that generates the components of the composite.

### Concrete Class
A class that is allowed to have instances.

### Concurrency
The modeling and coordination of independent and distinct computing activities whose execution spans may overlap in time.

### Continuation
Roughly, a representation of “the rest of the program.”

### Contravariance
A property of a type system that defines `T<U>` to be a subtype of `T<V>` whenever `U` is a **supertype** of `V`.
  
### Coroutine
A line of execution that, under explicit programmer control, can yield to other coroutines and be resumed later.

### Covariance
A property of a type system that defines `T<U>` to be a subtype of `T<V>` whenever `U` is a **subtype** of `V`.

### Curried Function
A function of one parameter that returns a function of one parameter, in contrast to a function that takes two parameters (or a pair of objects).

### Dangling Pointer
An in-scope pointer variable whose referenced memory has been freed.

### Deadlock
A situation in which two or more competing threads are blocked forever, each waiting for the other to finish.

### Decimal Type
A datatype that stores the decimal digits of numeric quantities.

### Decorator
An object providing additional behavior to another object.

### Deferred Execution
A block of code executed at some point in the future, generally in response to a triggering event.

### Deep Copy
A copy which recurses through an object graph, copying all referenced values.

### Dependent Type
A type that depends on a value or constraint, such as the type of trees with height 8, or the type of all sorted lists.

### Dereference
The evaluation of the the object referenced by a (pointer) variable.

### Destructor
Code (generally a function) executed when an object is destroyed.

### Dictionary
A set of key-value pairs, with unique keys. Also known as a **map**.

### Discriminated Union
See **tagged union**.

### Dynamic Language
A language in which tasks such as modifying code and adding types can be done at run time.

### Dynamic Typing
The state of having the types of some expressions not known until run time.

### Eager Evaluation
The evaluation of all of a function’s arguments (or an operator’s operand) _before_ application of the function (or operator). Also known as **strict evaluation**.

### Encapsulation
The bundling of data elements into a single component, often in a way that the constituent elements cannot be directly accessed.

### Encoding
(1) The representation, in bytes, of an entity. (2) A specification of how certain entities should be encoded in bytes.

### Entity
A semantic component of a program, that could, in principle, be named and processed by the running program. Examples include: variables, constants, functions, arrays, types, blocks, generators, and iterators.

### Enum
A dope word for **enumerated type**.

### Enumeration
A complete ordering of a given set of elements. The term may refer either to (1) a type whose constituent values are listed (an **enumerated type**) or (2) a sequence of values emitted by a generator.

### Enumerated Type
A type whose complete set of memebers is listed (enumerated) in the program.

### Event
An occurrence that can be detected and handled.

### Exception
An entity that is thrown, or raised, to abort the current normal control flow and transfer control to the point at which the exception is caught, if any.

### Expression
A construct in a program that is **evaluated** to produce a **value**.

### Falsy
Treated as false in a boolean context (e.g., when evaluating conditions).

### First-class
Able to be assigned to variables, passed as parameters, and returned from functions.

### Fixnum
An integer type represented with a fixed, finite, number of bits.

### Frame
A structure in the execution model of a program representing a particular activation of a [routine](#routine). A frame records the parameters and local variables of the activation, as well as additional bookkeeping information. Also known as an **activation record**.

### Function
A possibly parameterized, and possibly named, callable block of code.

### Functional Programming
A programming paradigm in which computation proceeds entirely by evaluating side-effect-free expressions, generally involving function calls.

### Future
See **promise**.

### Garbage Collection
The reclamation of storage holding objects that are no longer needed.

### Generic
Able to be specified just once and “work in about the same way” in many different contexts.

### Guard
A boolean expression used to allow (when true) or disallow (when false) access to an entity.

### Heap Storage
The portion of memory in which new objects are allocated (and deallocated) at run time. Sometimes simply called “the heap“.

### Higher-Order Function
A function that takes functions as arguments or returns functions.

### Homoiconicity
The property of a language in which code is represented as a data structure and both have the same syntactic forms.

### Hygienic Macro
A macro whose expansion will not capture identifiers.

### Identifier
A name for an entity in a program. (The set of identifiers allowed in a particular programming language often excludes the so-called **reserved words** or **keywords**.)

### Immutable
The quality of an entity whose state may not change.

### Inheritance
The property of a class or object acquiring the same structure or behavior of another entity, which can then be optionally specialized.

### Instance
An object (when referred to in reference to its class or interface).

### Interface
A programming structure that enforces certain behaviors on an object.

### Interoperability
The capability of two or more programming languages to interact and operate on shared data or invoke shared functions.

### Interpolation
The process of evaluating a string or object literal to yield a result in which placeholders are replaced with computed values.

### Iterator
An object that provides the capability to access the elements of a container in some order.

### JIT
Method of language translation in which the source language is translated _during_ interpretation, that is, (J)ust-(I)n-(T)ime.

### Keyword
A word with a special meaning in a programming language, such as "function", "while", or "if". (Note: a keyword may or may not be a [reserved word](#reserved-word).)

### Keyword Argument
An argument that is matched to a corresponding parameter using the parameter’s name, rather than by its position in a call.

### Lazy Evaluation
An evaluation strategy for expressions in which evaluation of subexpressions is delayed until an actual value is needed.

### Lexical Analysis
The phase of programming language translation or interpretation that groups individual characters into tokens (words and other symbols).

### Lifetime
The time between an objects’ creation and destruction.

### Literal
A representation of a value in source code.

### Lvalue
A storage location into which values can be assigned.

### Macro
A rule or pattern that specifies how an input should be mapped to a replacement output. Often used in the context of rewriting source code prior to compilation.

### Mailbox
A container for data into which one process writes data for another process to read (generally in an asynchronous fashion).

### Match
An object storing information regarding the successful location of a pattern in some data.

### Memoization
An optimization technique for repeatedly-called functions that caches results, and returns cached results when the same inputs occur.

### Metaclass
A class whose instances are classes.

### Method
A function intimately associated with an object.

### Module
A language construct wrapping a collection of (usually encapsulated) related entities, providing an interface to other modules of a system.

### Monad
Roughly, a type whose values are wrappings over a base type, supporting operations to (1) wrap a value and (2) associatively chain functions that produce wrapped values from unwrapped values; such that first function is both a left and right identity for the second. (Example: Lists and Optionals are monads: the first operation puts an item into a singleton list or optional; the second is the `flatMap` you know and love from JavaScript.)

### Monitor
An object or module providing mutually exclusive access among its clients to achieve thread safety.

### Nullish
A value representing the absence of a value (e.g., `null`) or the lack of information about a value (e.g., `undefined`)

### Object
(1) In C and other low-level languages, an entity in a program intended to be stored in memory. (2) In object-oriented programming, an instance of class.

### Operator
A function generally, though not necessarily, named with non-alphanumeric symbols that computes well-known (often algebraic) and widely applicable operations.

### Operator Overloading
The allowance for a single named operator to have different implementations depending on their arguments. For example, the name `*` can overload integer multiplication, floating-point multiplication, string repetition, vector dot product, or vector scalar product.

### Option Type
A type whose values are wrappers that either contain or do not contain a wrapped value.

### Parameter
A variable to which arguments are passed.

### Pass-by-Name
An argument passing mechanism in which an argument is not evaluated prior to a call, but rather within the function using (essentially) the text of the argument expression.

### Pass-by-Reference
An argument passing mechanism in which a reference to the argument is passed to the parameter, so that mutations through the parameter are immediately applied to the argument.

### Pass-by-Sharing
An argument passing mechanism in which only (a copy of) the object identifier of the argument is passed.

### Pass-by-Value
An argument passing mechanism in which an argument is evaluated and then (a copy is) subsequently passed to the parameter.

### Pass-by-Value Result
An argument passing mechanism in which an argument is evaluated before the call, passed by value to the corresponding parameter, and, after execution of the callee, any changes made to the parameter are copied to the corresponding argument.

### Persistent Data Structure
A data structure that retains the prior version of itself when modified.

### Pointer
An object that references a location in memory.

### Polymorphism
The allowance for a single name to be bound to multiple entities at the same time, generally with the understanding that any invocation of the name will refer to the desired entity based on context.

### Promise
Roughly, a placeholder for an (initially) unfinished computation. A promise is immediately returned when an asynchronous computation is launched to be queried later or used in a callback. Also known as a future, though in some contexts, futures and promises are distinguished.

### Prototype
(1) An object from which other objects are derived. (2) An object to which property requests are forwarded to by an object that does not own a property of a given name. (3) In C, a function signature.

### Proxy
An object that provides an interface to another object. The proxy takes requests on behalf of the proxied object and may modify or deny these requests before forwarding them to the proxied object.

### Reactive Programming
A programming style centered on streams of data that are managed asynchronously.

### Race Condition
The situtation in which the result of a section of multithreaded code depends on which thread ends up modifying a shared resource “first.“

### Receiver
In a method invocation, the object on which a method is invoked.

### Record
An object whose components are labeled values.

### Reference
An object that refers to another object, called its **referent**. Often used to allow sharing of data. A reference may be dereferenced to obtain the referent, but does not act on behalf of the reference as does a proxy.

### Regex
Another term for [Regular Expression](#regular-expression).

### Regular Expression
A pattern that describes sets of strings according to a large number of widely-accepted mechanisms, and sometimes with programming-language specific mechanisms.

### Reserved Word
A word in the syntax of a programming language that cannot be used as an [identifier](#identifier).

### Routine
A callable block of code, either a [subroutine](#subroutine) or [coroutine](#coroutine).

### Runtime
The period of time in which a program is being executed.

### Rvalue
A value that can be assigned. So named because traditional assignment statements are written with the destination storage location on the left (hence the term l-value) and the data to be assigned on the right (hence the term r-value).

### Scope
The region of source code in which a binding refers to a given entity.

### Scripting Language
(1) A language designed for running jobs, i.e., coordinating (or scripting) the activities of other programs. (2) A language low on “ceremony” but rich in expressive features, designed to allow its programmers to be productive.

### Second-class
An entity that is not allowed to be represented by a variable in an expression.

### Semantic Analysis
The phase of language translation or interpretation in which (1) legality rules that cannot be captured in a context-free syntax are checked, and (2) all identifier uses are resolved to determine the definitions that they reference.

### Semantics
Refers to the meaning of a program, as opposed to structure.

### Semaphore
A variable or object used to permit only a specific number of threads to access a shared resource at a time.

### Shallow Copy
A component-by-component copy of the values of the original object, in which references are not followed but are themselves copied.

### Sigil
A symbol affixed to a variable name that indicates something about the variable, such as its scope or type.

### Signal
A value that changes over time but that is processed as a stream.

### Signature
A specification of a function, method, or module that is completely free of implementation details, providing the minimum amount of information to use the object.

### Single Inheritance
The restriction of a type or class to have only a single supertype or superclass.

### Software Transactional Memory
A mechanism for controlling updates in a concurrent environment in which all updates within a marked transaction either happen (get committed) or are rolled back.

### Spread
An operator that expands a single expression into multiple expressions, within the context of a collection literal, argument list, or similar construct.

### Stack Storage
The location in memory used to store frames.

### Starvation
A scenario in which a process or thread cannot proceed because it is continually denied requests to resources it requires.

### Static Language
A language in which the vast majority of metadata (types of variables, which functions are called, etc.) can be inferred by examining source code only and not requiring execution to determine.

### Static Storage
The region of memory used to store data whose lifetime coincides with the entire program.

### Static Typing
The inference of and checking of types prior to execution.

### Stream
A sequence of objects made available over time.

### Strict Evaluation
An evaluation strategy in which all operands are evaluated before being given to an operator.

### Subclass
A class derived from another class, inheriting many of the original class’s properties and optionally adding its own properties and behaviors.

### Subrooutine
A callable block of code designed to run while the caller waits for it to finish.

### Superclass
A class that has been subclassed.

### Symbol
A named primitive entity whose value is, essentially, itself. Also known as an **atom**.

### Synchronous
A form of communication in which the caller must wait for the callee to be ready to accept the call, or in some cases, must wait for the callee to finish the requested service.

### Syntactic Salt
Syntactic forms that tend to make programs verbose, or difficult to follow, even though they may have been added to the language with good intentions.

### Syntactic Sugar
A syntactic form that improves upon an equivalent primitive form by being more concise, expressive, powerful, or elegant.

### Syntax
Refers to the structure of a program, as opposed its meaning.

### Systems Language
A programming language used for writing system software.

### Tagged Union
A union type whose members are each tagged with a label indicating the underlying type from which they came. Also known as a disjoint union, discriminated union, disjoint sum, or discriminated sum.

### Thread
A sequential flow of control, generally preemptible and generally able to share memory with other threads.

### Trait
A set of methods, generally expected to be mixed in to a class to enhance its behavior or to increase its capabilities.

### Transient
The property of any element in a system that is not persisted or serialized.

### Transpiler
A complier that changes the source code of a program written in one language to the equivalent source code in another programming language.

### Truthy
Treated as true in a boolean context (e.g., when evaluating conditions).

### Type
A set of values with common behavior enforced by the programming language.

### Type Compatibility
The property of a relationship between an expression e and type t in which e can be used in any context expecting a value of type t.

### Type Inference
Automatic deduction of the type of an expression.

### Type Variable
A variable that ranges over types.

### Union Type
A type whose set of values is the union of zero or more other types.

### Value
A unit of data or information.

### Variable
(1) An identifier bound to a value. (2) A storage location containing a value that can change.

### Volatile Variable
A variable that must be made available to multiple threads and thus cannot be implemented with multiple divergent copies per-thread.

### Wildcard
A character in a pattern meant to be replaced.
