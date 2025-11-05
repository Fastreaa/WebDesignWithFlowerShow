---
# FRONTMATTER (Metadatos)
# Ajusta esto en la primera línea de tu archivo
title: We are Creative Agency
description: La landing page principal de tu agencia.
layout: page # Usa un layout de página estándar
---
---
# FRONTMATTER (Metadatos)
title: We are Creative Agency
description: La landing page principal de tu agencia.
layout: page 
---

<HeroSection>
  <div 
    className="flex flex-col items-start p-10 md:p-20 text-white min-h-[60vh] relative overflow-hidden bg-cover bg-center" 
    style={{ backgroundImage: `url('/abstracfondo.png')`, backgroundColor: '#19194d' }}
  >
    
    {/* Contenido de Texto */}
    <h1 className="text-5xl md:text-7xl font-bold mb-4 z-10">
      We are <br />
      Creative Agency.
    </h1>
    <p className="text-lg mb-8 max-w-lg z-10">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, 
      sed do eiusmod tempor.
    </p>

    {/* Barra de Búsqueda */}
    <div className="flex w-full max-w-lg mb-8 z-10">
      <input 
        type="text" 
        placeholder="Search something here..."
        className="flex-grow p-4 text-gray-800 rounded-l-md border-2 border-white focus:outline-none" 
      />
      <button className="bg-blue-600 p-4 rounded-r-md hover:bg-blue-700">
        🔍 
      </button>
    </div>

    {/* Botones */}
    <div className="flex space-x-4 z-10">
      <button className="bg-blue-500 text-white font-semibold py-3 px-8 rounded-lg hover:bg-blue-600 transition duration-300">
        Sign In
      </button>
      <button className="bg-white text-blue-500 font-semibold py-3 px-8 rounded-lg border-2 border-blue-500 hover:bg-gray-100 transition duration-300">
        Sign Up
      </button>
    </div>

  </div>
</HeroSection>

## Nuestro Trabajo Reciente
Aquí puedes añadir más contenido en Markdown.
