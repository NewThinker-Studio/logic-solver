
## Naming

- namespace or class name:  UpperCamelCase (also named PascalCase)

- method name: lowerCamelCase

- member variable name: m_xxx_xxx

- normal varible name: xxx_xxxx

- macro name: XXX_XXX



## Comments

Only use ```//``` to comment a line.

NEVER USE ```/*``` AND ```*/``` PAIRS.



## Example code

```c++

#define EXAMPLE_MACRO "example macro"

namespace ExampleNameSpace {

  // Some introduction to class ExampleClass, some introduction to 
  // class ExampleClass. Some introduction to class ExampleClass,
  // some introduction to class ExampleClass.
  // 
  // Some introduction to class ExampleClass, some introduction to 
  // class ExampleClass. Some introduction to class ExampleClass,
  // some introduction to class ExampleClass.
  // 
  class ExampleClass {
  public:
    ExampleClass() {}

    // Some introduction to the method if necessary
    void set(int example_normal_varibale) {
      m_example_member_variable = example_normal_varibale;
    }

  private:
    // Some introduction to the member variable if necessary.
    int m_example_member_variable;
  }

} // namespace ExampleNameSpace

```


