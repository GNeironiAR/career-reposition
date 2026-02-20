# Diagnóstico de Perfil — Ejemplo de Output
## Profesional Tech LATAM vs. Rol de AI Solutions Engineer

**Contexto:** Este es un ejemplo real (anonimizado) del output que genera la Fase 2 del prompt. El profesional tiene +15 años en IT, healthcare, datos y cloud, trabaja remoto desde Argentina para clientes US, y está transicionando hacia el rol de AI Solutions Engineer.

---

## 1. Perfil del Candidato

| Aspecto | Detalle |
|---------|---------|
| **Experiencia** | +15 años en IT, healthcare informatics, datos y cloud |
| **Ubicación** | Argentina (remoto para clientes US) |
| **Rol actual** | Cloud Data Engineer en empresa de consulting |
| **Producto propio #1** | SaaS FinOps con IA — escanea cuentas AWS, detecta desperdicio y genera código IaC con LLMs |
| **Producto propio #2** | Marketplace B2B de logística — conecta oferta y demanda de transporte de carga |

---

## 2. Evaluación por Área del Rol

### Escala: 🟢 Sólido (>75%) | 🟡 En desarrollo (40-75%) | 🔴 Gap significativo (<40%)

---

### 2.1 Cloud Computing & IaC — 🟢 95%

| Competencia | Evidencia | Estado |
|---|---|---|
| AWS core (EC2, S3, Lambda, RDS, IAM, VPC) | Uso diario en todos los proyectos | 🟢 |
| AWS CDK (Python) | Ambos productos propios desplegados 100% con CDK | 🟢 |
| Arquitectura serverless | Lambda + API Gateway + DynamoDB + EventBridge + Step Functions | 🟢 |
| Arquitectura híbrida (Lambda + ECS Fargate) | Ambos productos usan combinación serverless + containers | 🟢 |
| CI/CD (GitHub Actions) | Implementado en múltiples proyectos y productos propios | 🟢 |
| VPC, networking, ALB | VPC con subnets públicas/privadas, ALB con SSL, VPC peering en proyecto ETL | 🟢 |
| Data lake (Glue, Athena, Lake Formation) | Múltiples implementaciones en consulting | 🟢 |
| Docker / Containerización | Lambda containers + ECS Fargate en producción | 🟢 |
| FinOps | El producto propio #1 es literalmente una herramienta FinOps | 🟢 |
| Multi-cloud (Azure) | Experiencia previa + certificaciones Azure | 🟡 |

**Certificaciones:** AWS Cloud Practitioner, especializaciones en data analytics, Azure Fundamentals + Data Engineering  
**En progreso:** AWS Solutions Architect Associate

---

### 2.2 Desarrollo Full-Stack — 🟢 90%

| Competencia | Evidencia | Estado |
|---|---|---|
| Python (backend, scripting, Lambda) | Lenguaje principal en todos los proyectos | 🟢 |
| FastAPI | Backend de ambos productos propios | 🟢 |
| React + TypeScript | Frontend completo del marketplace (routing, contexts, hooks, i18n, Google Maps) | 🟢 |
| PostgreSQL + PostGIS | DB principal del marketplace con búsqueda geoespacial | 🟢 |
| SQL avanzado | SQL Server, Oracle, MySQL, PostgreSQL — 15+ años | 🟢 |
| APIs REST (diseño y consumo) | 50+ endpoints en un producto, integraciones con Stripe, pasarelas de pago, APIs externas | 🟢 |
| JWT authentication | Implementación propia con sistema de 7 roles y matriz de permisos granular | 🟢 |
| Integración de pagos | Stripe + MercadoPago en productos distintos | 🟢 |
| Integración de mapas | Google Maps (Places, Geocoding, Distance Matrix) + PostGIS | 🟢 |

---

### 2.3 Integración de IA / LLMs — 🟡 55%

| Competencia | Evidencia | Estado |
|---|---|---|
| Uso de APIs de LLMs (Claude, Bedrock) | Producto FinOps genera código IaC via Claude API. Otro proyecto usa Bedrock | 🟢 |
| Prompt engineering aplicado | Prompts dinámicos almacenados en DB, templates con variables, output formatting | 🟢 |
| RAG (Retrieval-Augmented Generation) | Pipeline de document intelligence (Textract → Bedrock → Graph). Proyecto QA bot | 🟡 |
| AI Agents | Diseño conceptual de agentes multi-step, sin producción madura | 🟡 |
| AI pair-coding (Claude, Cursor) | Uso intensivo diario como herramienta de desarrollo | 🟢 |
| ML fundamentals | Certificación en ML, uso de SageMaker Canvas. Conocimiento teórico, poca práctica profunda | 🟡 |
| Fine-tuning de modelos | Revisión de modelos fine-tuned, sin implementación propia | 🔴 |
| Vector databases | Sin implementación directa | 🔴 |
| LangChain / LangGraph | Sin uso en producción | 🔴 |

**Observación clave:** Ya usa IA en producción (LLM generando código IaC, Bedrock para análisis). Lo que falta es profundidad en frameworks de orquestación y fundamentals de ML más allá de APIs.

---

### 2.4 Diseño de Sistemas y Arquitectura — 🟢 95%

| Competencia | Evidencia | Estado |
|---|---|---|
| Arquitecturas cloud complejas | Dos productos con arquitecturas distintas (serverless + containers), ETL pipelines con VPC peering | 🟢 |
| Modelo de datos relacional complejo | 7 dominios, 10+ entidades, relaciones polimórficas, extensiones geoespaciales | 🟢 |
| Decisiones build vs buy documentadas | JWT propio vs Auth0, APScheduler vs Celery, CDK vs Terraform — con razones documentadas | 🟢 |
| Ciclo completo idea → deploy (x2) | Dos SaaS propios: concepto → pricing → arquitectura → código → infra → CI/CD → producción/staging | 🟢 |
| Event-driven architectures | EventBridge, S3 events → Lambda, Step Functions, scheduled jobs | 🟢 |
| Documentación formal | 10+ documentos de arquitectura, ADRs, diagramas, flujos | 🟢 |
| Seguridad en capas | Security Groups en cascada, SSM sin SSH, presigned URLs, secrets inyectados | 🟢 |

---

### 2.5 Pensamiento de Producto y Negocio — 🟢 80%

| Competencia | Evidencia | Estado |
|---|---|---|
| Traducir negocio → solución técnica | 15 años en healthcare + consulting + 2 startups propias | 🟢 |
| Pricing y monetización | Gainshare + suscripción con pricing escalonado por volumen | 🟢 |
| TAM/SAM/SOM | Análisis completo documentado para uno de los productos | 🟢 |
| KPIs y métricas | 5 KPIs semanales con targets y alertas + triggers de abandono | 🟢 |
| Proyecciones financieras | MRR/ARR a 3 años, break-even calculado, costos operativos detallados | 🟢 |
| Validación con prototipos | Beta que identificó $18K/mes en savings para un cliente real | 🟢 |
| Product management formal | Sin frameworks formales (OKRs, discovery) | 🟡 |

---

### 2.6 Liderazgo Técnico — 🟡 55%

| Competencia | Evidencia | Estado |
|---|---|---|
| Gestión de equipos | IT Manager (26 personas) en experiencia previa | 🟢 |
| Thought leadership | LinkedIn actualizado, primeras métricas de visibilidad. Sin contenido técnico regular todavía | 🟡 |
| Open source | Repos públicos pero sin tracción comunitaria | 🟡 |
| Mentoría técnica | Sin evidencia directa | 🔴 |
| ADRs documentadas | 8+ decisiones arquitectónicas documentadas con justificación | 🟢 |

---

## 3. Mapa de Cobertura

```
Área                          Cobertura    Nivel    Tendencia
═══════════════════════════════════════════════════════════════
Cloud & IaC                   95%          🟢       → estable
Desarrollo Full-Stack         90%          🟢       ⬆ subió
Integración de IA/LLMs        55%          🟡       → gap principal
Diseño de Sistemas            95%          🟢       ⬆ subió
Producto y Negocio            80%          🟢       ⬆ subió
Liderazgo Técnico             55%          🟡       ⬆ leve
═══════════════════════════════════════════════════════════════
PROMEDIO PONDERADO            78%
```

---

## 4. Los 3 Gaps Críticos

### Gap 1: Profundidad en AI/ML más allá de APIs
**Qué falta:** Frameworks de orquestación (LangChain, LangGraph, CrewAI), vector databases, agents en producción, fundamentals de ML sólidos.  
**Por qué importa:** Ya usa IA en producción, pero el mercado pide pipelines de IA complejos, no solo llamadas a APIs.  
**Acción:** Cursos de DeepLearning.AI (RAG, Agents, LangChain) + cert AWS AI Practitioner + implementar feature de IA en el segundo producto.  
**Tiempo estimado:** 2-3 meses (5-8 hrs/semana).

### Gap 2: Certificación de arquitectura cloud formal
**Qué falta:** AWS Solutions Architect Associate. El conocimiento práctico está, falta la validación formal.  
**Por qué importa:** Es la certificación cloud más reconocida globalmente. Con esta experiencia, es low-hanging fruit.  
**Acción:** Plan de estudio de 7 semanas ya en ejecución.

### Gap 3: Posicionamiento y thought leadership
**Qué falta:** Presencia como referente técnico público. Contenido técnico regular.  
**Por qué importa:** En 2026, ser visible es tan importante como ser competente.  
**Acción:** LinkedIn ya actualizado. Pendiente: publicar casos técnicos, crear contenido regular, completar actualización de website.

---

## 5. Diferenciadores Competitivos

1. **Dos SaaS propios en producción/staging** — en dominios distintos (FinOps + logística). La mayoría de candidatos no tienen ni uno.
2. **15 años de dominio cruzado** — Healthcare + datos + cloud + negocio. Combinación rara y valiosa.
3. **IaC como segunda naturaleza** — Ambos productos desplegados con CDK Python.
4. **Ciclo completo demostrado x2** — Desde pricing hasta VPC peering, desde pagos hasta CI/CD. En dos dominios distintos.
5. **Full-stack real** — React + TypeScript + FastAPI + PostgreSQL/PostGIS + pagos + mapas + AWS ECS + CDK. Todo en producción/staging.
6. **Consultoría activa** — Múltiples clientes US simultáneos mientras construye dos productos propios.

---

## 6. Proyección Post-Plan (6 meses)

```
Área                          Hoy    →  +6 meses    Cambio
═══════════════════════════════════════════════════════════════
Cloud & IaC                   95%    →  98%         +cert SAA
Desarrollo Full-Stack         90%    →  90%         estable
Integración de IA/LLMs        55%    →  75%         +cursos +feature IA
Diseño de Sistemas            95%    →  95%         estable
Producto y Negocio            80%    →  85%         +thought leadership
Liderazgo Técnico             55%    →  70%         +contenido +portfolio
═══════════════════════════════════════════════════════════════
PROMEDIO PONDERADO            78%    →  86%
```

---

*Ejemplo real anonimizado — generado con el prompt de Career Repositioning.*  
*Los nombres de productos, clientes y datos de ingreso fueron removidos o generalizados.*
