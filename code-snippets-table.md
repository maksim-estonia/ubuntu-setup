<table>
<tr>
<td> Keyword </td> <td> Output </td>
</tr>
<tr>
<td> #def </td> 
<td>

```cpp
#define "" "" 
```

</td>
</td>
<tr>
<td> #if </td> 
<td>

```cpp
#ifdef 0

#endif // 0
```

</td>
</tr>
<tr>
<td> #ifdef </td> 
<td>

```cpp
#ifdef DEBUG

#endif // DEBUG
```

</td>
</tr>
<tr>
<td> #ifndef </td> 
<td>

```cpp
#ifndef 1

#endif // !1
```

</td>
</tr>
<tr>
<td> #inc </td> 
<td>

```cpp
#include "" 
```

</td>
</tr>
<tr>
<td> #inc< </td> 
<td>

```cpp
#include <> 
```

</td>
</tr>
<tr>
<td> class </td> 
<td>

```cpp
class MyClass
{
public:
    MyClass();
    MyClass(MyClass &&) = default;
    MyClass(const MyClass &) = default;
    MyClass &operator=(MyClass &&) = default;
    MyClass &operator=(const MyClass &) = default;
    ~MyClass();

private:
    
};

MyClass::MyClass()
{
}

MyClass::~MyClass()
{
} 
```

</td>
</tr>
<tr>
<td> classi </td> 
<td>

```cpp
class MyClass
{
public:
    MyClass() = default;
    MyClass(MyClass &&) = default;
    MyClass(const MyClass &) = default;
    MyClass &operator=(MyClass &&) = default;
    MyClass &operator=(const MyClass &) = default;
    ~MyClass() = default;

private:
    
};
```

</td>
</tr>
<tr>
<td> cout </td> 
<td>

```cpp
std::cout << "/* message */" << std::endl; 
```

</td>
</tr>
<tr>
<td> do </td> 
<td>

```cpp
do
{
    
} while();
```

</td>
</tr>
<tr>
<td> else </td> 
<td>

```cpp
else
{
    
}
```

</td>
</tr>
<tr>
<td> else if </td> 
<td>

```cpp
else if ()
{
    
}
```

</td>
</tr>
<tr>
<td> enum </td> 
<td>

```cpp
enum MyEnum
{
    
};
```

</td>
</tr>
<tr>
<td> enum class </td> 
<td>

```cpp
enum class MyClass { };
```

</td>
</tr>
<tr>
<td> for </td> 
<td>

```cpp
for (size_t i = 0; i < length; i++)
{
    
}
```

</td>
</tr>
<tr>
<td> foreach </td> 
<td>

```cpp
for(auto var : collection_to_loop)
{
    
}
```

</td>
</tr>
<tr>
<td> forr </td> 
<td>

```cpp
for (int i = length - 1; i >= 0; i--)
{
    
}
```

</td>
</tr>
<tr>
<td> if </td> 
<td>

```cpp
if ()
{
    
}
```

</td>
</tr>
<tr>
<td> interface </td> 
<td>

```cpp
__interface IInterface
{
    
};
```

</td>
</tr>
<tr>
<td> main </td> 
<td>

```cpp
int main(int argc, const char** argv) {
    return 0;
}
```

</td>
</tr>
<tr>
<td> namespace </td> 
<td>

```cpp
namespace MyNamespace
{
    
}
```

</td>
</tr>
<tr>
<td> struct </td> 
<td>

```cpp
struct MyStruct
{
    
};
```

</td>
</tr>
<tr>
<td> switch </td> 
<td>

```cpp
switch (switch_on)
{
default:
    break;
}
```

</td>
</tr>
<tr>
<td> try </td> 
<td>

```cpp
try
{
    
}
catch (const std::exception&)
{
    
} 
```

</td>
</tr>
<tr>
<td> union </td> 
<td>

```cpp
union MyUnion
{
    
};
```

</td>
</tr>
<tr>
<td> while </td> 
<td>

```cpp
while ()
{
    
}
```

</td>
</tr>

</table>
