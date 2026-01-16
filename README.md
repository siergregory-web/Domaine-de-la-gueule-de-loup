socialhub/
├── public/
│   └── index.html
├── src/
│   ├── social-app.jsx      # Composant principal
│   ├── App.js              # Point d'entrée
│   └── index.js
├── package.json
└── README.md
import React from 'react';
import SocialApp from './social-app';

function App() {
  return <SocialApp />;
}

export default App;
background: 'linear-gradient(135deg, #667eea 0%, #764ba2 100%)'
// Remplacez par vos couleurs préférées
