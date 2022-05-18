# MY SQL
**DML**

Sentecias:
- SELECT
- INSERT
- UPDATE
- DELETE
---

**SELECT**

Selecciona los atributos que se desean

**INTO**

**FROM**

De que Tabla proviene los datos que necesitas

**WHERE**

Condiciones que debe seguir las filas que estoy mostrando

SELECT, FROM Y WHERE son aplicados para la sentencia base

```SQL
SELECT Dato
FROM TABLE1
WHERE DATO > 0
```

**GROUP BY**

Agrupamientos de las tablas

**HAVING**

**ORDER BY**

Ordenar desde el máximo

```SQL
ORDER BY 2 DESC 
```

Ordenar desde el mínimo

```SQL
ORDER BY 1 DESC 
```

**UNION**

---
Diferencia entre SUM Y COUNT
---

|       a          |
|------------------|
1
2
3



SUM = 6

COUNT = 3

---

JOINS
--

```SQL
SELECT SUM(Quantity) AS TOTAL
FROM TABLE1 TA1
    JOIN TABLE2 TA2 ON TA1.Order = TA2.Order
```

---

MAXIMO
--

```SQL
SELECT Category, MAX(Total) FROM TABLE1
```

---

DISTINCT
--

Sirve para que no tome valores repetidos
Quiero saber los valores distintos

```SQL
SELECT DISTINCT CustomerID
FROM (Orders) ORDER BY 1
```

En este caso ordena desde el 1

