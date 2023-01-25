import React, { useState } from 'react';

const Navigation = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);

  const handleMenuToggle = () => {
    setIsMenuOpen(!isMenuOpen);
  };

  return (
    <div className="navigation">
      <div className={`navigation__links ${isMenuOpen ? 'is-open' : ''}`}>
        <a href="#">Inicio</a>
        <a href="#">Info</a>
        <a href="#">Contacto</a>
      </div>
      <button className="navigation__menu-button" onClick={handleMenuToggle}>
        {isMenuOpen ? 'Close' : 'Menu'}
      </button>
    </div>
  );
};

export default Navigation;
