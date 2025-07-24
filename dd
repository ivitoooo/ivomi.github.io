import React from "react";

const navLinks = [
  { name: "Inicio", href: "#" },
  { name: "Propiedades", href: "#propiedades" },
  { name: "Servicios", href: "#servicios" },
  { name: "Nosotros", href: "#nosotros" },
  { name: "Contacto", href: "#contacto" },
];

const propiedades = [
  {
    titulo: "Residencia de Lujo en Puerto Madero",
    descripcion: "Departamento premium con vista al río, amenities exclusivos y cochera privada.",
    img: "https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80",
    precio: "USD 1.250.000",
  },
  {
    titulo: "Casa Moderna en Barrio Privado",
    descripcion: "5 ambientes, pileta, seguridad 24hs. Excelente entorno y conectividad.",
    img: "https://images.unsplash.com/photo-1568605114967-8130f3a36994?auto=format&fit=crop&w=600&q=80",
    precio: "USD 720.000",
  },
  {
    titulo: "Oficina Premium en Microcentro",
    descripcion: "Piso completo, terminaciones de categoría, ideal empresas.",
    img: "https://images.unsplash.com/photo-1507089947368-19c1da9775ae?auto=format&fit=crop&w=600&q=80",
    precio: "USD 430.000",
  },
];

export default function App() {
  return (
    <div className="font-sans text-gray-800 bg-gray-50 min-h-screen">
      {/* Nav */}
      <header className="bg-[#336699] shadow-lg fixed w-full z-30">
        <nav className="container mx-auto px-6 py-4 flex justify-between items-center">
          <span className="text-2xl font-bold text-white tracking-wide">
            Tarjan Brokers
          </span>
          <ul className="hidden md:flex gap-8">
            {navLinks.map((link) => (
              <li key={link.name}>
                <a
                  href={link.href}
                  className="text-white text-lg font-medium hover:underline hover:text-gray-200 transition"
                >
                  {link.name}
                </a>
              </li>
            ))}
          </ul>
        </nav>
      </header>
      <main className="pt-24">
        {/* Hero */}
        <section className="bg-[#336699] text-white py-20">
          <div className="container mx-auto px-6 flex flex-col md:flex-row items-center gap-12">
            <div className="flex-1">
              <h1 className="text-5xl font-extrabold mb-6 leading-tight drop-shadow-lg">
                Inmobiliaria de Prestigio<br />
                <span className="text-[#aaccee]">Tarjan Brokers</span>
              </h1>
              <p className="text-lg mb-8 max-w-xl">
                Asesoría personalizada, excelencia y confianza. <br />
                Más de 25 años brindando soluciones de alto nivel en el mercado inmobiliario argentino.
              </p>
              <a
                href="https://wa.me/5491151136264?text=Hola%20Tarjan%20Brokers,%20quiero%20más%20info."
                target="_blank"
                rel="noopener noreferrer"
                className="bg-white text-[#336699] font-semibold px-7 py-3 rounded-2xl shadow-md hover:bg-[#aaccee] hover:text-[#25496a] transition"
              >
                Contactar ahora
              </a>
            </div>
            <img
              src="https://images.unsplash.com/photo-1464983953574-0892a716854b?auto=format&fit=crop&w=600&q=80"
              alt="Edificio elegante"
              className="rounded-2xl shadow-2xl w-full max-w-md object-cover"
            />
          </div>
        </section>
        {/* Propiedades Destacadas */}
        <section id="propiedades" className="container mx-auto px-6 py-16">
          <h2 className="text-3xl font-bold mb-10 text-[#336699]">
            Propiedades destacadas
          </h2>
          <div className="grid md:grid-cols-3 gap-8">
            {propiedades.map((p, i) => (
              <div
                key={i}
                className="bg-white rounded-2xl shadow-xl hover:shadow-2xl transition flex flex-col"
              >
                <img
                  src={p.img}
                  alt={p.titulo}
                  className="rounded-t-2xl w-full h-52 object-cover"
                />
                <div className="p-6 flex-1 flex flex-col">
                  <h3 className="font-semibold text-xl mb-2">{p.titulo}</h3>
                  <p className="mb-4 flex-1">{p.descripcion}</p>
                  <span className="text-[#336699] font-bold text-lg">{p.precio}</span>
                </div>
              </div>
            ))}
          </div>
        </section>
        {/* Servicios */}
        <section id="servicios" className="bg-[#336699] text-white py-16">
          <div className="container mx-auto px-6">
            <h2 className="text-3xl font-bold mb-10">Servicios exclusivos</h2>
            <div className="grid md:grid-cols-3 gap-10">
              <div>
                <h3 className="font-semibold text-xl mb-2">Venta y Alquiler Premium</h3>
                <p>
                  Comercialización de propiedades residenciales, comerciales y campos. Foco en inmuebles de categoría.
                </p>
              </div>
              <div>
                <h3 className="font-semibold text-xl mb-2">Asesoría Legal y Notarial</h3>
                <p>
                  Equipo propio de abogados y escribanos. Seguridad y respaldo total en cada operación.
                </p>
              </div>
              <div>
                <h3 className="font-semibold text-xl mb-2">Gestión de Inversiones</h3>
                <p>
                  Armado de carteras inmobiliarias, análisis de mercado y oportunidades para grandes inversores.
                </p>
              </div>
            </div>
          </div>
        </section>
        {/* Nosotros */}
        <section id="nosotros" className="container mx-auto px-6 py-16">
          <div className="md:flex gap-12 items-center">
            <div className="flex-1">
              <h2 className="text-3xl font-bold mb-4 text-[#336699]">
                ¿Quiénes somos?
              </h2>
              <p className="text-lg mb-4">
                Tarjan Brokers es sinónimo de excelencia y seriedad en el rubro inmobiliario argentino.  
                Nuestro equipo está conformado por profesionales experimentados, dedicados a ofrecer un servicio de calidad y resultados concretos.  
                Nos eligen por nuestra atención personalizada, conocimiento del mercado y valores inquebrantables.
              </p>
              <ul className="mb-2 list-disc list-inside">
                <li>Trayectoria de 25 años en el mercado</li>
                <li>Red de contactos exclusiva</li>
                <li>Gestión integral y confidencial</li>
              </ul>
            </div>
            <img
              src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80"
              alt="Equipo Tarjan Brokers"
              className="rounded-2xl shadow-lg w-full max-w-sm object-cover mt-8 md:mt-0"
            />
          </div>
        </section>
        {/* Contacto */}
        <section id="contacto" className="bg-[#336699] text-white py-16">
          <div className="container mx-auto px-6 max-w-xl">
            <h2 className="text-3xl font-bold mb-6">Contacto</h2>
            <div className="mb-4">
              <p className="text-lg">
                También podés escribirnos a{" "}
                <a
                  href="mailto:tarjanbrokers@gmail.com"
                  className="underline font-semibold hover:text-[#aaccee]"
                >
                  tarjanbrokers@gmail.com
                </a>
                {" "}o por{" "}
                <a
                  href="https://wa.me/5491151136264?text=Hola%20Tarjan%20Brokers,%20quiero%20más%20info."
                  target="_blank"
                  rel="noopener noreferrer"
                  className="underline font-semibold hover:text-[#aaccee]"
                >
                  WhatsApp
                </a>
                .
              </p>
            </div>
            <form className="space-y-6">
              <input
                type="text"
                placeholder="Nombre y apellido"
                className="w-full rounded-xl px-4 py-3 text-[#336699] font-semibold focus:outline-none"
              />
              <input
                type="email"
                placeholder="Correo electrónico"
                className="w-full rounded-xl px-4 py-3 text-[#336699] font-semibold focus:outline-none"
              />
              <textarea
                rows={4}
                placeholder="Tu consulta"
                className="w-full rounded-xl px-4 py-3 text-[#336699] font-semibold focus:outline-none"
              ></textarea>
              <button
                type="submit"
                className="bg-white text-[#336699] font-bold px-7 py-3 rounded-2xl shadow-md hover:bg-[#aaccee] hover:text-[#25496a] transition w-full"
              >
                Enviar mensaje
              </button>
            </form>
          </div>
        </section>
      </main>
      <footer className="bg-[#25496a] text-white text-center py-6">
        © {new Date().getFullYear()} Tarjan Brokers Inmobiliarios. Todos los derechos reservados.
      </footer>
    </div>
  );
}
