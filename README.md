# clean-code-in-python
<p>
what is clean code?
</p>
<p>
is a set of rules and priciples that helps to keep our code readable, maintainable and extendable.
</p>
<p>
- Use long descriptive names that are easy to read to remove the need for writing unnecessary comments
for ex :
</p>

```
#Not recommended
#The x variable is the number of orders
x = 105

#Recommended 
number-of-orders= 105
```

<p>
- Use descriptive intention revealing names to make it easy for developers to know what your variable stores from the name.
</p>

```
# Not recommended
N = [“Ahmed”, “Mohamed”, “Abdullah”]

for x in N:
print(x)
# Recommended
Names = [“Ahmed”, “Mohamed”, “Abdullah”]
    for Name in Names:
        print(Name)

```

<p>
-Avoid using ambiguous shorthand.A variable should have a long descriptive name than a short confusing name.
</p>

```
# Not recommended
fn = 'Abdelrahman'
Ln = ‘Alaa’
# Recommended
first_name = ‘Abdelrahman’
Las_name = ‘Alaa’
```

<p>
-Always use the same vocabulary. Maintaining a consistent naming convention is important to eliminate confusion when other developers work on your code.
</p>

```
# Not recommended
client_first_name = ‘John’
customer_last_name = ‘Doe;

# Recommended
client_first_name = ‘John’
client_last_name = ‘Doe’

```

<p>
- Be consistent with your function naming convention because Using different naming conventions would confuse other developers.
</p>

```
# Not recommended
def get_users(): 
    # do something
    Pass

def fetch_user(id): 
    # do something
    Pass

# Recommended
def fetch_users(): 
    # do something
    Pass

def fetch_user(id): 
    # do something
    Pass
```
