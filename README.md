// App.js
import React from 'react';

function App() {
  const products = [
    { id: 1, name: 'لعبة أطفال', price: 50 },
    { id: 2, name: 'حقيبة مدرسية', price: 80 },
    { id: 3, name: 'حليب أطفال', price: 30 },
  ];

  return (
    <div>
      <h1>تطبيق تسوق حضانة</h1>
      <ul>
        {products.map(product => (
          <li key={product.id}>
            {product.name} - السعر: {product.price} ريال
          </li>
        ))}
      </ul>
    </div>
  );
}

export default App;
# Paradise-Nursery-Shopping-App
