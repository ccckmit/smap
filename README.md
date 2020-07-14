# smap -- Simple-Map

```rs
        let mut e2c = Dict::new();
        e2c.add("a", "一隻");
        e2c.add("dog", "狗");
        e2c.add("cat", "貓");
        e2c.add("chase", "追");
        e2c.add("bite", "咬");
        assert!(e2c.get("cat") != None);
        assert!(e2c.get("xxx") == None);
```
