:root {
  --bg: #f7f8f4;
  --surface: #ffffff;
  --text: #1d2f21;
  --muted: #5a6d63;
  --primary: #4c9a2a;
  --primary-dark: #3d7a21;
  --border: #dce3d6;
  --shadow: 0 16px 40px rgba(18, 34, 20, 0.08);
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  background: linear-gradient(180deg, #f2f5ef 0%, #fcfcfb 100%);
  color: var(--text);
  min-height: 100vh;
}

.hero {
  padding: 3rem 1.5rem 2rem;
  background: linear-gradient(135deg, #e8f4d7 0%, #ffffff 100%);
  border-bottom: 1px solid var(--border);
}

.hero-text {
  max-width: 720px;
  margin: 0 auto;
  text-align: center;
}

.eyebrow {
  margin: 0 0 0.75rem;
  font-size: 0.95rem;
  color: var(--primary-dark);
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

h1 {
  margin: 0;
  font-size: clamp(2.5rem, 5vw, 4rem);
  line-height: 1.02;
}

p {
  margin: 1rem 0 0;
  line-height: 1.8;
  color: var(--muted);
}

.container {
  display: grid;
  grid-template-columns: 1.4fr 0.85fr;
  gap: 1.75rem;
  max-width: 1240px;
  margin: 0 auto;
  padding: 2rem 1.5rem 3rem;
}

section,
.cart-panel {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 24px;
  box-shadow: var(--shadow);
}

.section-header {
  padding: 1.75rem 1.75rem 0;
}

.section-header h2 {
  margin: 0;
  font-size: 1.6rem;
}

.products-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  padding: 1.5rem;
}

.product-card {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  padding: 1.25rem;
  background: #f7f9f3;
  border-radius: 20px;
  border: 1px solid transparent;
  transition: border-color 0.2s ease, transform 0.2s ease;
}

.product-card:hover {
  transform: translateY(-2px);
  border-color: #d1e4c1;
}

.product-card h3 {
  margin: 0;
  font-size: 1.15rem;
}

.product-card .tag {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  padding: 0.35rem 0.6rem;
  background: rgba(76, 154, 42, 0.14);
  color: var(--primary-dark);
  border-radius: 999px;
  font-size: 0.8rem;
}

.product-card p {
  margin: 0;
  color: var(--muted);
  font-size: 0.95rem;
}

.product-footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 0.75rem;
}

.price {
  font-weight: 700;
  font-size: 1.05rem;
}

button.add-btn,
.checkout-btn,
.cart-action {
  border: none;
  border-radius: 999px;
  padding: 0.95rem 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: transform 0.2s ease, background-color 0.2s ease;
}

button.add-btn {
  background: var(--primary);
  color: #ffffff;
}

button.add-btn:hover,
.checkout-btn:hover,
.cart-action:hover {
  transform: translateY(-1px);
}

.cart-panel {
  display: flex;
  flex-direction: column;
  min-height: 420px;
}

.cart-items {
  padding: 0 1.75rem;
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.cart-item {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 1rem;
  align-items: center;
  padding: 1rem;
  border: 1px solid #eef2e8;
  border-radius: 18px;
  background: #fbfdf7;
}

.cart-item div {
  display: flex;
  flex-direction: column;
  gap: 0.3rem;
}

.cart-item h3 {
  margin: 0;
  font-size: 1rem;
}

.cart-controls {
  display: inline-flex;
  gap: 0.5rem;
}

.cart-action {
  min-width: 2.6rem;
  min-height: 2.6rem;
  background: #e7f0d9;
  color: var(--primary-dark);
}

.cart-summary {
  padding: 1.5rem 1.75rem 2rem;
  border-top: 1px solid #edf2e5;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.cart-summary div {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 0.5rem;
}

.checkout-btn {
  width: 100%;
  background: var(--primary);
  color: #fff;
}

.checkout-btn:disabled {
  opacity: 0.6;
  cursor: not-allowed;
}

.footer {
  padding: 1.25rem 1.5rem 2.5rem;
  text-align: center;
  color: var(--muted);
}

@media (max-width: 980px) {
  .container {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 680px) {
  .hero {
    padding-top: 2rem;
  }

  .products-grid {
    padding: 1rem;
  }

  .cart-items {
    padding: 1rem;
  }
}
