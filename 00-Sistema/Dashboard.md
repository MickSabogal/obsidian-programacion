# 🧭 Índice de programación
- [[Índice de programación]]

# Fundamentos

## 🎯 En progreso:

```dataview  
list
from "02-fundamentos"  
where status = "en_progreso"  
sort file.name asc
```
## 🚀 Proximamente:

- [ ] [[CSS]]
- [ ] [[Flexbox]]
- [ ] [[Grid]]
- [ ] [[Bootstrap]]
- [ ] [[JavaScript]]
- [ ] [[Jquery]]
- [ ] [[Git]]
- [ ] [[Node.js]]
- [ ] [[EJS]]
- [ ] [[APIs]]
- [ ] [[Base de datos]]
- [ ] [[SQL]]
- [ ] [[ProgreSQL]]
- [ ] [[Authentication & Security]]
- [ ] [[React]]
- [ ] [[Web 3.0]]

## ✅Completado:

```dataview
list
from "02-fundamentos"  
where status = "completado"  
sort file.name asc
```

# Hoy:

```dataview  
list
from "02-fundamentos"  
where status = "en_progreso"  
sort file.name asc
```

# Proyectos

## 🎯 En progreso:

```dataview  
list
from "03-proyectos"  
where status = "en_progreso" 
```

## ✅Completado:

```dataview  
TABLE  
tipo as "Tipo",
progreso + "%" as "Avance"     
FROM "03-proyectos" 
WHERE status = "completado"  
SORT date 
```
