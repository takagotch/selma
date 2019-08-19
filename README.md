### selma
---
https://github.com/xebia-france/selma

```java
@Mapper
public interface SelmaMapper {
  OutBean asOutBean(InBean source);
  
  OutBean updateOutBean(InBean source, OutBean desination);
}

SelmaMapper mapper = Selma.mapper(SelemaMapper.class);
OutBean res = mapper.asOutBean(in);
OutBean dest = dao.getById(42);
OutBean res = mapper.updateOutBean(in, dest);

```

```
```

```
```


