---
title: One Page Website Inspiration
description: Plantillas y recursos para sitios de una sola página.
layout: page
---

<HeroSection>
  <div
    className="flex flex-col items-center justify-center pt-20 pb-16 bg-gray-900 text-white min-h-[40vh] text-center"
  >
    
    <div className="max-w-4xl mx-auto px-4">
      <h1 className="text-5xl font-extrabold mb-4">
        One Page website inspiration, templates and resources
      </h1>
      <p className="text-lg max-w-3xl mb-8">
        Since 2008, we have curated 8149 Single Page websites. Learn more about us or submit and get featured to 150k designers, devs & makers each month.
      </p>

      {/* Botón CTA derecho */}
      <a href="/newsletter" className="bg-pink-600 text-white font-semibold py-3 px-8 rounded-full hover:bg-pink-700 inline-block mt-4">
        INSCRIPTION NEWSLETTER ↗
      </a>
    </div>

  </div>
</HeroSection>

{/* SECCIÓN DE CONTENIDO PRINCIPAL (El Área de Tarjetas Claras) */}
<div className="max-w-6xl mx-auto px-4 py-16">

<div className="text-center mb-8">
    <h3 className="uppercase text-sm font-semibold tracking-widest text-gray-500">LATEST WEBSITE INSPIRATION</h3>
</div>

<div className="grid grid-cols-1 md:grid-cols-3 gap-8">
  
  {/* Tarjeta 1 */}
  <div className="bg-white shadow-lg border border-gray-100 rounded-lg overflow-hidden">
    <img src="/assets/design-systems.jpg" alt="Are design systems overrated?" className="w-full h-48 object-cover"/>
    <div className="p-6">
      <h3 className="text-xl font-bold mb-2">Are design systems overrated?</h3>
      <p className="text-sm text-gray-500">Featured Article</p>
    </div>
  </div>

  {/* Tarjeta 2 */}
  <div className="bg-white shadow-lg border border-gray-100 rounded-lg overflow-hidden">
    <img src="/assets/hongo-theme.jpg" alt="Hongo - WordPress Theme" className="w-full h-48 object-cover"/>
    <div className="p-6">
      <h3 className="text-xl font-bold mb-2">Hongo - WordPress Theme</h3>
      <p className="text-sm text-gray-500">Featured Template</p>
    </div>
  </div>

  {/* Tarjeta 3 */}
  <div className="bg-white shadow-lg border border-gray-100 rounded-lg overflow-hidden">
    <img src="/assets/figma-webflow.jpg" alt="Design in Figma, launch in Webflow" className="w-full h-48 object-cover"/>
    <div className="p-6">
      <h3 className="text-xl font-bold mb-2">Design in Figma, launch in Webflow</h3>
      <p className="text-sm text-gray-500">Recommended</p>
    </div>
  </div>
</div>

</div>
