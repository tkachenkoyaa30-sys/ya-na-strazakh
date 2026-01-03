digital-store/
├── app/
│   ├── layout.tsx
│   ├── page.tsx                 // Главная
│   ├── globals.css
│   ├── not-found.tsx
│   │
│   ├── shop/
│   │   ├── page.tsx             // Каталог
│   │   ├── category/
│   │   │   └── [slug]/page.tsx
│   │   └── product/
│   │       └── [slug]/page.tsx  // Страница макета
│   │
│   ├── portfolio/
│   │   └── page.tsx
│   │
│   ├── about/page.tsx
│   ├── contacts/page.tsx
│   │
│   ├── success/page.tsx
│   │
│   ├── download/
│   │   └── [token]/route.ts     // Скачивание
│   │
│   └── api/
│       ├── prodamus/route.ts    // Webhook
│       ├── order/route.ts       // Создание заказа
│       └── email/route.ts
│
├── components/
│   ├── ui/
│   │   ├── Button.tsx
│   │   ├── Modal.tsx
│   │   └── Input.tsx
│   │
│   ├── ProductCard.tsx
│   ├── Gallery.tsx
│   ├── Header.tsx
│   ├── Footer.tsx
│   └── WatermarkImage.tsx
│
├── lib/
│   ├── cms.ts                   // запросы к CMS
│   ├── prodamus.ts
│   ├── storage.ts               // S3 / R2
│   ├── tokens.ts
│   ├── email.ts
│   └── seo.ts
│
├── types/
│   ├── product.ts
│   ├── order.ts
│   └── category.ts
│
├── public/
│   ├── images/
│   └── fonts/
│
├── styles/
│   └── tailwind.config.ts
│
├── middleware.ts                // защита, редиректы
├── .env.example                  // шаблон переменных
├── next.config.js
├── package.json
└── README.md
