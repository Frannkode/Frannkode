```aura width=860 height=200
<div style={{
  width: '100%', height: '100%', background: '#0d0d0d',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(255,255,255,0.12)'
}}>

  <style>{`
      @keyframes float-slow {
        0%, 100% { transform: translateX(0px); opacity: 0.7; }
        50% { transform: translateX(350px); opacity: 1.0; }
      }
      @keyframes float-medium {
        0%, 100% { transform: translateX(0px); opacity: 0.6; }
        50% { transform: translateX(-250px); opacity: 0.9; }
      }
      @keyframes float-fast {
        0%, 100% { transform: translateX(0px); opacity: 0.8; }
        50% { transform: translateX(200px); opacity: 0.5; }
      }
      #glow-1 { animation: float-slow 8s ease-in-out infinite; }
      #glow-2 { animation: float-medium 12s ease-in-out infinite; }
      #glow-3 { animation: float-fast 9s ease-in-out infinite; }
      #glow-4 { animation: float-slow 11s ease-in-out infinite reverse; }
    `}</style>

  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,255,255,0.18)" />
        <stop offset="60%" stopColor="rgba(255,255,255,0.05)" />
        <stop offset="100%" stopColor="rgba(255,255,255,0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(200,200,200,0.15)" />
        <stop offset="60%" stopColor="rgba(200,200,200,0.04)" />
        <stop offset="100%" stopColor="rgba(200,200,200,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(150,150,150,0.14)" />
        <stop offset="60%" stopColor="rgba(150,150,150,0.03)" />
        <stop offset="100%" stopColor="rgba(150,150,150,0)" />
      </radialGradient>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,255,255,0.10)" />
        <stop offset="70%" stopColor="rgba(255,255,255,0)" />
      </radialGradient>
    </defs>

    <ellipse id="glow-1" cx="180" cy="230" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="300" cy="240" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="240" rx="180" ry="140" fill="url(#g3)" />
    <ellipse id="glow-4" cx="750" cy="250" rx="130" ry="110" fill="url(#g4)" />
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 52, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #ffffff, #999999)',
    display: 'flex', alignItems: 'center', justifyContent: 'center', overflow: 'hidden',
  }}>
    <img src="https://raw.githubusercontent.com/Frannkode/Frannkode/main/Broly.png" width={96} height={96} style={{ borderRadius: 48, objectFit: 'cover' }} />
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:168, gap:8, zIndex: 10 }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:800, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      Frannkode
    </div>
    <div style={{ display:'flex', fontSize:15, color:'rgba(220,220,220,0.8)', fontWeight:400, letterSpacing:'0.3px' }}>
      Full Stack Developer · React + Vite · React Native + Firebase
    </div>
    <div style={{ display:'flex', gap:8, marginTop:6, flexWrap: 'wrap' }}>
      {['React', 'React Native', 'FastAPI', 'Firebase', 'Tailwind'].map(function(tag, i) {
        return (
          <div key={tag + '-' + i} style={{
            display:'flex', padding:'4px 12px', borderRadius:20,
            background:'rgba(255,255,255,0.08)', border:'1px solid rgba(255,255,255,0.18)',
            color:'rgba(230,230,230,0.9)', fontSize:12, fontWeight:600,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

<br>

<table width="100%">
<tr>
<td width="63%" valign="top">

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMXlibG9xZHJ5cjBzODFzZGs2MzZwajhvbmh0cXY0eDFwNjQ3cjludiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Y2I4hn3pQvGSxXnO2i/giphy.gif" width="100%" />

<p align="center">
<b>Frannkode</b> · Full Stack Developer<br/>
<sub>Reconquista, Santa Fe, Argentina</sub>
</p>

</td>
<td width="37%" valign="top">

```aura width=310 height=95
<div style={{
  width: '100%', height: '100%', background: '#0d0d0d',
  display: 'flex', flexDirection: 'column', justifyContent: 'center', fontFamily: 'Inter',
  borderRadius: 14, border: '1px solid rgba(255,255,255,0.12)', padding: '0 24px'
}}>
  <div style={{ display: 'flex', fontSize: 12, color: 'rgba(200,200,200,0.6)', fontWeight: 600, letterSpacing: '0.5px' }}>QUICK STATS</div>
  <div style={{ display: 'flex', gap: 18, marginTop: 10 }}>
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <div style={{ display: 'flex', fontSize: 22, fontWeight: 800, color: '#ffffff' }}>{github?.stats?.totalRepos ?? '12+'}</div>
      <div style={{ display: 'flex', fontSize: 11, color: 'rgba(200,200,200,0.55)' }}>repos</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <div style={{ display: 'flex', fontSize: 22, fontWeight: 800, color: '#ffffff' }}>{github?.stats?.totalStars ?? '0'}</div>
      <div style={{ display: 'flex', fontSize: 11, color: 'rgba(200,200,200,0.55)' }}>stars</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <div style={{ display: 'flex', fontSize: 22, fontWeight: 800, color: '#ffffff' }}>{github?.user?.followers ?? '0'}</div>
      <div style={{ display: 'flex', fontSize: 11, color: 'rgba(200,200,200,0.55)' }}>followers</div>
    </div>
  </div>
</div>
```

<br>

```aura width=310 height=95
<div style={{
  width: '100%', height: '100%', background: '#0d0d0d',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  borderRadius: 14, border: '1px solid rgba(255,255,255,0.12)', padding: '0 24px'
}}>
  <div style={{
    width: 10, height: 10, borderRadius: 5, background: '#ffffff', marginRight: 14,
  }} />
  <div style={{ display: 'flex', flexDirection: 'column' }}>
    <div style={{ display: 'flex', fontSize: 13, color: 'rgba(200,200,200,0.6)', fontWeight: 600, letterSpacing: '0.5px' }}>FOCUSING</div>
    <div style={{ display: 'flex', fontSize: 15, color: '#ffffff', fontWeight: 700, marginTop: 4 }}>Open to freelance work</div>
  </div>
</div>
```

</td>
</tr>
</table>

```aura width=130 height=44 link="https://github.com/Frannkode" inline align=center
<SocialMediaButton icon="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/github.svg" text="GitHub" backgroundColor="#0d0d0d" textColor="#ffffff" width={130} height={44} borderColor="rgba(255,255,255,0.3)" iconSize={16} />
```
```aura width=130 height=44 link="mailto:poncefrancomiguel@gmail.com" inline align=center
<SocialMediaButton icon="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/gmail.svg" text="Email" backgroundColor="#0d0d0d" textColor="#ffffff" width={130} height={44} borderColor="rgba(255,255,255,0.3)" iconSize={16} />
```
```aura width=130 height=44 link="https://linkedin.com/in/tecfrancoponce" inline align=center
<SocialMediaButton icon="data:image/svg+xml;utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='%23ffffff' d='M14 3v2h3.59L7 15.59 8.41 17 19 6.41V10h2V3h-7zM5 5v14h14v-7h-2v5H7V7h5V5H5z'/%3E%3C/svg%3E" text="LinkedIn" backgroundColor="#0d0d0d" textColor="#ffffff" width={130} height={44} borderColor="rgba(255,255,255,0.3)" iconSize={16} />
```
```aura width=130 height=44 link="https://frannkode.vercel.app" inline align=center
<SocialMediaButton icon="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/vercel.svg" text="Portfolio" backgroundColor="#0d0d0d" textColor="#ffffff" width={130} height={44} borderColor="rgba(255,255,255,0.3)" iconSize={16} />
```

<br>

<h2 align="center">👨‍💻 <em>About me</em></h2>

```aura width=760 height=230
<div style={{
  width: '100%', height: '100%', background: '#0d0d0d',
  display: 'flex', flexDirection: 'column', justifyContent: 'center', fontFamily: 'Inter',
  borderRadius: 16, border: '1px solid rgba(255,255,255,0.12)', padding: '0 40px', gap: 14
}}>
  <div style={{ display: 'flex', fontSize: 15, color: 'rgba(220,220,220,0.85)', lineHeight: 1.5 }}>
    Hola! Soy Franco, Full Stack Developer. Me gusta armar apps con React, React Native y Firebase, y meterme también en el backend con FastAPI. Sumando experiencia en proyectos freelance y trabajo bajo metodología Scrum.
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: 8, marginTop: 6 }}>
    <div style={{ display: 'flex', fontSize: 14, color: '#ffffff' }}>• Formación técnica en UTN (Programación)</div>
    <div style={{ display: 'flex', fontSize: 14, color: '#ffffff' }}>• Freelance / consultoría en desarrollo web y e-commerce</div>
    <div style={{ display: 'flex', fontSize: 14, color: '#ffffff' }}>• Trabajo en equipos Scrum, tickets en Jira</div>
    <div style={{ display: 'flex', fontSize: 14, color: '#ffffff' }}>• Reconquista, Santa Fe, Argentina</div>
  </div>
</div>
```

<br>

<h2 align="center">⚙️ <em>Technologies</em></h2>

```aura width=760 height=140
<div style={{
  width: '100%', height: '100%', background: '#0d0d0d',
  display: 'flex', alignItems: 'center', justifyContent: 'center', flexWrap: 'wrap', fontFamily: 'Inter',
  borderRadius: 16, border: '1px solid rgba(255,255,255,0.12)', padding: '20px 30px', gap: 10
}}>
  {['JavaScript', 'TypeScript', 'React', 'React Native', 'Vite', 'TailwindCSS', 'Python', 'FastAPI', 'Firebase', 'PostgreSQL', 'Git', 'Jira'].map(function(tech, i) {
    return (
      <div key={tech + '-' + i} style={{
        display: 'flex', padding: '8px 16px', borderRadius: 20,
        background: 'rgba(255,255,255,0.06)', border: '1px solid rgba(255,255,255,0.16)',
        color: '#ffffff', fontSize: 13, fontWeight: 600,
      }}>{tech}</div>
    );
  })}
</div>
```

<br>

<h2 align="center">🧬 <em>Top Languages</em></h2>

```aura width=760 height=110
<div style={{
  width: '100%', height: '100%', background: '#0d0d0d',
  display: 'flex', flexDirection: 'column', justifyContent: 'center', fontFamily: 'Inter',
  borderRadius: 16, border: '1px solid rgba(255,255,255,0.12)', padding: '18px 32px', gap: 10
}}>
  {((github && github.languages && github.languages.length > 0)
    ? github.languages.slice(0, 5)
    : [
        { name: 'JavaScript', percentage: 45, color: '#f1e05a' },
        { name: 'TypeScript', percentage: 30, color: '#3178c6' },
        { name: 'HTML', percentage: 15, color: '#e34c26' },
        { name: 'Python', percentage: 10, color: '#3572A5' },
      ]
  ).map(function(lang, i) {
    return (
      <div key={lang.name + '-' + i} style={{ display: 'flex', alignItems: 'center', gap: 10 }}>
        <div style={{ display: 'flex', width: 90, fontSize: 12, color: 'rgba(220,220,220,0.8)', fontWeight: 600 }}>{lang.name}</div>
        <div style={{ display: 'flex', width: 480, height: 8, borderRadius: 4, background: 'rgba(255,255,255,0.08)' }}>
          <div style={{ display: 'flex', width: Math.max(6, Math.round(lang.percentage * 4.8)), height: 8, borderRadius: 4, background: '#ffffff' }} />
        </div>
        <div style={{ display: 'flex', fontSize: 12, color: 'rgba(200,200,200,0.6)' }}>{Math.round(lang.percentage)}%</div>
      </div>
    );
  })}
</div>
```

<h2 align="center">🚀 <em>Featured Projects</em></h2>

<p align="center">
  <a href="https://github.com/Frannkode/ViciosBurger"><b>ViciosBurger</b></a> · React Native app for food delivery<br/>
  <a href="https://github.com/Frannkode/ViciosBurgerApp"><b>ViciosBurgerApp</b></a> · PWA version of the delivery app<br/>
  <a href="https://github.com/Frannkode/ReactVicios"><b>ReactVicios</b></a> · Mobile-first menu with WhatsApp ordering<br/>
  <a href="https://github.com/Frannkode/ElCruceRestaurant"><b>ElCruceRestaurant</b></a> · Restaurant site, React + Tailwind v4<br/>
  <a href="https://github.com/Frannkode/Innovare"><b>Innovare</b></a> · Web app built with Create React App<br/>
  <a href="https://github.com/Frannkode/Portfolio-Web"><b>Portfolio-Web</b></a> · My personal portfolio, React 19 + Framer Motion<br/>
  <a href="https://github.com/Frannkode/ATARAXIA"><b>ATARAXIA</b></a> · TypeScript project<br/>
  <a href="https://github.com/Frannkode/QuickOrder"><b>QuickOrder</b></a> · TypeScript ordering system<br/>
  <a href="https://github.com/Frannkode/FullBebidas"><b>FullBebidas</b></a> · E-commerce site for beverages<br/>
  <a href="https://github.com/Frannkode/Indumentaria"><b>Indumentaria</b></a> · E-commerce site for clothing<br/>
  <a href="https://github.com/Frannkode/MotoPartes"><b>MotoPartes</b></a> · E-commerce site for motorcycle parts<br/>
  <a href="https://github.com/Frannkode/Parras"><b>Parras</b></a> · JavaScript project
</p>

<br>

<h2 align="center">📊 <em>Statistics</em></h2>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Frannkode&bg_color=0d0d0d&color=ffffff&line=ffffff&point=ffffff&area=true&hide_border=false" width="100%"/>
</div>
