The .scss (Sass) files are only available in the pro version.
You can buy it from: https://bootstrapmade.com/kelly-free-// ==============================
// Header Logo Alignment Fix
// ==============================
.header {
  background-color: #f5f5f5; // keep your header background
  display: flex;
  align-items: center;
  padding: 10px 20px;

  .logo {
    display: flex;
    align-items: center;
    justify-content: flex-start;

    img {
      height: 60px; // adjust this for your logo height
      width: auto;
      object-fit: contain;
      display: block;
      vertical-align: middle;
      margin-top: 4px; // centers vertically with text
    }
  }

  // Navbar spacing alignment
  #navmenu {
    display: flex;
    align-items: center;
    gap: 30px;

    ul {
      display: flex;
      align-items: center;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    li a {
      font-family: "Poppins", sans-serif;
      font-weight: 500;
      font-size: 16px;
      color: #333;
      transition: color 0.3s ease;

      &:hover,
      &.active {
        color: #34b7a7; // highlight color
      }
    }
  }

  // Right-side social icons
  .header-social-links {
    display: flex;
    align-items: center;
    gap: 15px;

    a {
      color: #555;
      font-size: 18px;
      transition: color 0.3s ease;

      &:hover {
        color: #34b7a7;
      }
    }
  }
}

// Responsive adjustment
@media (max-width: 768px) {
  .header {
    flex-wrap: wrap;
    justify-content: space-between;

    .logo img {
      height: 50px;
      margin-top: 0;
    }
  }
}
-cv-resume-html-template/