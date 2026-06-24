<div className="min-h-screen bg-black text-white font-sans">

{/* HERO */}
<section className="px-8 md:px-20 py-28 bg-gradient-to-br from-black via-slate-900 to-cyan-950">

<div className="max-w-6xl mx-auto grid md:grid-cols-2 gap-16 items-center">

<div>

<p className="text-cyan-400 text-xl mb-4 animate-pulse">
🤖 AI/ML Engineer | Data Analyst | GenAI Developer
</p>


<h1 className="text-6xl md:text-8xl font-extrabold leading-tight">

Sanskriti
<span className="text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500">
 Wasalwar
</span>

</h1>


<p className="mt-8 text-gray-300 text-xl leading-9">

Building intelligent AI systems using Machine Learning,
Generative AI, NLP, Predictive Analytics and modern
Full Stack technologies.

</p>


<div className="flex gap-5 mt-10">

<button className="px-8 py-4 rounded-2xl bg-cyan-500 text-black font-bold hover:scale-110 transition">
View Projects 🚀
</button>


<button className="px-8 py-4 rounded-2xl border border-cyan-400 text-cyan-400 hover:bg-cyan-400 hover:text-black transition">
Resume
</button>

</div>


</div>


{/* AI PROFILE */}

<div className="flex justify-center">

<div className="w-96 h-96 rounded-full bg-gradient-to-r from-cyan-400 to-blue-600 p-1 shadow-2xl">

<div className="w-full h-full rounded-full bg-black flex items-center justify-center">

<span className="text-8xl">
🧠
</span>

</div>

</div>

</div>


</div>

</section>



{/* ABOUT */}

<section className="px-8 md:px-20 py-24">

<div className="max-w-6xl mx-auto">


<h2 className="text-5xl font-bold text-cyan-400 mb-12">
About Me
</h2>


<div className="bg-slate-900 rounded-3xl p-10 border border-slate-800">


<p className="text-gray-300 text-lg leading-9">

I am an AI/ML enthusiast focused on building
real-world intelligent applications.

My expertise includes Machine Learning,
Deep Learning, Data Analytics, NLP, GenAI,
and Business Intelligence solutions.

I love transforming raw data into meaningful
insights and scalable AI products.

</p>


</div>


</div>

</section>




{/* SKILLS */}

<section className="bg-slate-950 px-8 md:px-20 py-24">


<h2 className="text-5xl font-bold text-cyan-400 mb-12">
Machine Learning Stack
</h2>



<div className="grid md:grid-cols-4 gap-6">


{[
"Python",
"Machine Learning",
"Scikit-learn",
"Deep Learning",
"NLP",
"Generative AI",
"OpenAI API",
"LangChain",
"SQL",
"Power BI",
"Streamlit",
"TensorFlow",
"Flask",
"React",
"MongoDB",
"AWS"
].map((skill)=>(


<div
key={skill}
className="
bg-slate-900
p-6
rounded-3xl
text-center
font-bold
border border-slate-800
hover:border-cyan-400
hover:-translate-y-2
transition
">

{skill}

</div>


))}


</div>

</section>





{/* PROJECTS */}


<section className="px-8 md:px-20 py-24">


<h2 className="text-5xl font-bold text-cyan-400 mb-12">
AI Projects
</h2>



<div className="grid md:grid-cols-2 gap-10">


{[

{
title:"🚀 ToxiShield AI",
desc:"Enterprise AI moderation system using NLP, Toxic-BERT, GenAI rewriting, emotion detection and analytics."
},


{
title:"📊 InsightX AI",
desc:"Customer intelligence platform with ML forecasting, user behavior analysis and business dashboards."
},


{
title:"💳 AI Fraud Detection",
desc:"Machine learning fraud detection system using Logistic Regression and Random Forest."
},


{
title:"📈 CryptoPulse AI",
desc:"Real-time market analytics pipeline with ML forecasting and anomaly detection."
}

].map((project)=>(


<div className="
bg-slate-900
p-8
rounded-3xl
border border-slate-800
hover:shadow-cyan-500/30
hover:shadow-2xl
transition
">


<h3 className="text-3xl font-bold mb-5">
{project.title}
</h3>


<p className="text-gray-300 leading-8">
{project.desc}
</p>


<button className="mt-6 text-cyan-400">
View Details →
</button>


</div>


))}


</div>

</section>




{/* CONTACT */}

<section className="bg-slate-900 py-24 text-center">


<h2 className="text-5xl font-bold text-cyan-400">
Let's Build AI Future 🚀
</h2>


<p className="text-gray-300 mt-6 text-xl">
Open for AI/ML internships, collaborations and innovative projects.
</p>



<div className="flex justify-center gap-6 mt-10">


<button className="bg-cyan-500 text-black px-8 py-4 rounded-2xl">
LinkedIn
</button>


<button className="border border-cyan-400 px-8 py-4 rounded-2xl text-cyan-400">
GitHub
</button>


<button className="border border-cyan-400 px-8 py-4 rounded-2xl text-cyan-400">
Email
</button>


</div>


</section>



<footer className="py-8 text-center text-gray-500">

© 2026 Sanskriti Wasalwar | AI/ML Portfolio

</footer>


</div>
