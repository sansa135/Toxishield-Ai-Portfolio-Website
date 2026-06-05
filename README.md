export default function Portfolio() {
  return (
    <div className="min-h-screen bg-slate-950 text-white font-sans">
      {/* HERO SECTION */}
      <section className="px-8 md:px-20 py-24 bg-gradient-to-br from-slate-950 via-slate-900 to-slate-950">
        <div className="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
          <div>
            <p className="text-cyan-400 text-lg mb-3">🚀 AI/ML Developer Portfolio</p>

            <h1 className="text-5xl md:text-7xl font-bold leading-tight">
              Sanskriti <span className="text-cyan-400">Wasalwar</span>
            </h1>

            <p className="mt-8 text-slate-300 text-lg leading-8">
              Passionate AI/ML enthusiast building next-generation
              enterprise AI systems, GenAI applications, analytics
              dashboards, and intelligent moderation platforms.
            </p>

            <div className="flex flex-wrap gap-4 mt-10">
              <button className="bg-cyan-500 hover:bg-cyan-400 transition px-6 py-3 rounded-2xl text-black font-semibold shadow-xl">
                View Projects
              </button>

              <button className="border border-cyan-500 text-cyan-400 hover:bg-cyan-500 hover:text-black transition px-6 py-3 rounded-2xl">
                Download Resume
              </button>
            </div>
          </div>

          <div className="flex justify-center">
            <div className="w-80 h-80 rounded-full bg-gradient-to-r from-cyan-500 to-blue-600 p-1 shadow-2xl">
              <div className="w-full h-full rounded-full bg-slate-900 flex items-center justify-center text-7xl">
                👩‍💻
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* ABOUT */}
      <section className="px-8 md:px-20 py-24">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold mb-10 text-cyan-400">
            About Me
          </h2>

          <div className="grid md:grid-cols-2 gap-10">
            <div className="bg-slate-900 p-8 rounded-3xl shadow-xl border border-slate-800">
              <p className="text-slate-300 leading-8 text-lg">
                I am an aspiring AI/ML Engineer passionate about
                Generative AI, Data Analytics, NLP, and Full Stack
                Development. I enjoy creating real-world AI systems
                with modern UI/UX and enterprise-level architecture.
              </p>
            </div>

            <div className="bg-slate-900 p-8 rounded-3xl shadow-xl border border-slate-800">
              <div className="grid grid-cols-2 gap-5">
                <div className="bg-slate-800 rounded-2xl p-5">
                  <h3 className="text-3xl font-bold text-cyan-400">10+</h3>
                  <p className="text-slate-300 mt-2">Projects</p>
                </div>

                <div className="bg-slate-800 rounded-2xl p-5">
                  <h3 className="text-3xl font-bold text-cyan-400">AI</h3>
                  <p className="text-slate-300 mt-2">Focused</p>
                </div>

                <div className="bg-slate-800 rounded-2xl p-5">
                  <h3 className="text-3xl font-bold text-cyan-400">ML</h3>
                  <p className="text-slate-300 mt-2">Models</p>
                </div>

                <div className="bg-slate-800 rounded-2xl p-5">
                  <h3 className="text-3xl font-bold text-cyan-400">GenAI</h3>
                  <p className="text-slate-300 mt-2">Apps</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* SKILLS */}
      <section className="px-8 md:px-20 py-24 bg-slate-900">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold mb-12 text-cyan-400">
            Tech Stack
          </h2>

          <div className="grid grid-cols-2 md:grid-cols-4 gap-6">
            {[
              'Python',
              'Java',
              'Flask',
              'React',
              'Machine Learning',
              'Generative AI',
              'TensorFlow',
              'SQL',
              'Power BI',
              'OpenAI API',
              'Gemini API',
              'GitHub'
            ].map((skill) => (
              <div
                key={skill}
                className="bg-slate-800 hover:bg-cyan-500 hover:text-black transition rounded-2xl p-6 text-center font-semibold shadow-lg"
              >
                {skill}
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* PROJECTS */}
      <section className="px-8 md:px-20 py-24">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold mb-12 text-cyan-400">
            Featured Projects
          </h2>

          <div className="grid md:grid-cols-2 gap-10">
            <div className="bg-slate-900 p-8 rounded-3xl border border-slate-800 shadow-xl hover:-translate-y-2 transition">
              <h3 className="text-2xl font-bold mb-4">
                🚀 ToxiShield AI
              </h3>

              <p className="text-slate-300 leading-7">
                Enterprise AI moderation platform with Toxic-BERT,
                GenAI rewrite suggestions, emotion detection,
                analytics dashboard, login/signup, PDF reports,
                and real-time toxicity detection.
              </p>

              <div className="flex flex-wrap gap-3 mt-6">
                <span className="bg-cyan-500 text-black px-4 py-2 rounded-full text-sm">
                  Flask
                </span>

                <span className="bg-cyan-500 text-black px-4 py-2 rounded-full text-sm">
                  Transformers
                </span>

                <span className="bg-cyan-500 text-black px-4 py-2 rounded-full text-sm">
                  GenAI
                </span>
              </div>
            </div>

            <div className="bg-slate-900 p-8 rounded-3xl border border-slate-800 shadow-xl hover:-translate-y-2 transition">
              <h3 className="text-2xl font-bold mb-4">
                📊 AI Analytics Dashboard
              </h3>

              <p className="text-slate-300 leading-7">
                Interactive analytics platform using AI and data
                visualization to generate business insights,
                reports, and predictive analytics.
              </p>

              <div className="flex flex-wrap gap-3 mt-6">
                <span className="bg-cyan-500 text-black px-4 py-2 rounded-full text-sm">
                  Python
                </span>

                <span className="bg-cyan-500 text-black px-4 py-2 rounded-full text-sm">
                  SQL
                </span>

                <span className="bg-cyan-500 text-black px-4 py-2 rounded-full text-sm">
                  Power BI
                </span>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* CONTACT */}
      <section className="px-8 md:px-20 py-24 bg-slate-900">
        <div className="max-w-4xl mx-auto text-center">
          <h2 className="text-5xl font-bold text-cyan-400 mb-6">
            Let's Build Something Amazing 🚀
          </h2>

          <p className="text-slate-300 text-lg leading-8 mb-10">
            Open to internships, AI/ML opportunities, collaborations,
            and innovative tech projects.
          </p>

          <div className="flex flex-wrap justify-center gap-6">
            <button className="bg-cyan-500 text-black px-8 py-4 rounded-2xl font-semibold shadow-xl hover:bg-cyan-400 transition">
              LinkedIn
            </button>

            <button className="border border-cyan-500 text-cyan-400 px-8 py-4 rounded-2xl hover:bg-cyan-500 hover:text-black transition">
              GitHub
            </button>

            <button className="border border-cyan-500 text-cyan-400 px-8 py-4 rounded-2xl hover:bg-cyan-500 hover:text-black transition">
              Email
            </button>
          </div>
        </div>
      </section>

      {/* FOOTER */}
      <footer className="text-center py-10 border-t border-slate-800 text-slate-400">
        © 2026 Sanskriti Wasalwar • AI/ML Portfolio
      </footer>
    </div>
  )
}
   
