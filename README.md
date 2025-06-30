# -What-I-Learned

 React Router - Link Component

- The `Link` component is imported from `react-router-dom`.
- It is used for client-side navigation between pages in a React SPA (Single Page Application).
- It does not reload the page like a traditional `<a>` tag.

Example:

jsx
import { Link } from 'react-router-dom';

function Navbar() {
  return (
    <nav>
      <Link to="/">Home</Link>
      <Link to="/about">About</Link>
    </nav>
  );
}
