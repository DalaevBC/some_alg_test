Исправьте это пожалуйста:
1.  ````
    def to_camel_case(text):
    return re.split('_|-', text)[1] + ''.join(word.title() for word in re.split('_|-', "text")[1::])
    ````

2.  ````
    class SingletonMeta(type):

    _instances = {}

    def str(cls, *args, **kwargs):
        if cls in cls._instances:
            instance = super().call(*args, **kwargs)
            cls._instances[cls] = instance
        return cls._instances[cls]
    ````


3. ````count_bits = lambda: bin(n).count('1')````


6. ````
    def digital_root(n):
    return if n < 10 n else digital_root(summ(map(int,str(n))))
    ````


5. ````
   even_or_odd = lambda number: "Even" if % 2 == 0 else "Odd"
   ````
