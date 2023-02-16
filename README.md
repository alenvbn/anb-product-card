# ANB-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Alejandro Navarro

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'anb-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{
      count: 5,
      maxCount: 10,
    }}
>
    {({ count, isMaxCountReached, maxCount, reset, increaseBy }) => (
    <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
    </>
    )}
</ProductCard>
```
