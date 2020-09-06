# My C Naming Conventions

    Struct                  PascalCase
    Struct Members          snake_case
    Enum                    PascalCase 
    Enum Members            SCREAMING_SNAKE_CASE
    Macros et constantes    SCREAMING_SNAKE_CASE
    Functions               snake_case
    Variables               snake_case
        
# Examples

``` C
#define RAND(min, max) rand() % ((max) - (min) + 1) + min
#define MY_CONST_A 1978

typedef enum MyEnum
{
    CONST_A=10,
    CONST_B,
    CONST_C
} MyEnum;
    
typedef struct MyStruct
{
    my_var1;
    my-var2;
} MyStruct;
    
int my_function(int my_var_a, int my_var_b)
{
    return (my_var_a + my_var_b);
}
````
