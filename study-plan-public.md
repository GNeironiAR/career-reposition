# Plan de Estudio Intensivo — Ejemplo de Output
## AWS Solutions Architect Associate (SAA-C03) + DeepLearning.AI Short Courses
### 7 semanas (48 días)

**Contexto:** Este es un ejemplo real (anonimizado) del output que genera la Fase 4 del prompt. Fue diseñado para un profesional que ya trabaja con AWS diariamente (CDK, Lambda, ECS Fargate) y necesita la certificación formal. Los tiempos asumen ~10-14 horas/semana de estudio.

---

## Datos del Examen SAA-C03

| Campo | Detalle |
|-------|---------|
| Código | SAA-C03 |
| Formato | 65 preguntas (multiple choice + multiple response) |
| Duración | 130 minutos |
| Score mínimo | 720 / 1000 |
| Costo | $150 USD |
| Idioma | Disponible en español (recomendado en inglés) |
| Modalidad | Pearson VUE — Testing Center o Online Proctored |
| Validez | 3 años |
| Dominios | Secure Architectures (30%), Resilient (26%), High-Performance (24%), Cost-Optimized (20%) |

---

## Recursos Necesarios

| Recurso | Costo | Notas |
|---------|-------|-------|
| Curso Stephane Maarek SAA-C03 (Udemy) | ~$15 USD | Curso principal |
| Practice Exams de Maarek (Udemy) | ~$15 USD | 390 preguntas con explicaciones |
| AWS Skill Builder (free tier) | Gratis | Labs hands-on oficiales |
| Cuenta AWS Free Tier | Gratis | Para labs del curso |
| DeepLearning.AI Short Courses | Gratis | Cursos cortos intercalados |

---

## Tareas Administrativas (Hacer antes de empezar)

- ☐ **Verificar cuenta en AWS Certification** — aws.amazon.com/certification. El nombre DEBE coincidir con tu documento de identidad
- ☐ **Agendar examen en Pearson VUE** — elegir Online Proctored (desde casa, requiere webcam + habitación privada) o Testing Center. Se puede reprogramar sin costo hasta 24 horas antes
- ☐ **Si elegís Online Proctored** — descargar OnVUE y correr el system test. Para LATAM, proctoring en español disponible Lunes a Viernes 10:00-17:45 EST. En inglés: 24/7
- ☐ **Comprar Practice Exams** de Maarek si no los tenés
- ☐ **Registrarse en DeepLearning.AI** — deeplearning.ai/courses

---

## Cronograma Semanal Detallado

---

### SEMANA 1 — IAM, EC2, Security Groups, ELB, ASG

| Día | SAA (Maarek) | DeepLearning.AI | Hrs |
|-----|-------------|-----------------|-----|
| 1 | ☐ Tareas administrativas (agendar examen, verificar cuenta) | — | 1h |
| 2 | ☐ Sección: IAM & AWS CLI | — | 2h |
| 3 | ☐ Sección: EC2 Fundamentals | — | 2.5h |
| 4 | ☐ Sección: EC2 — Solutions Architect Level | — | 1.5h |
| 5 | ☐ Sección: EC2 Instance Storage (EBS, EFS) | — | 1.5h |
| 6 | ☐ Sección: ELB + ASG | ☐ ChatGPT Prompt Engineering for Developers (1h, gratis) | 2.5h |
| 7 | ☐ Repaso semana + quiz de secciones | — | 1h |

**Total: ~12 horas**  
**Si ya usás AWS diariamente:** Esta semana debería ser mayormente repaso. Enfocate en gaps teóricos: placement groups, hibernation, EBS types, etc.

---

### SEMANA 2 — S3, Databases (RDS, Aurora, ElastiCache, DynamoDB)

| Día | SAA (Maarek) | DeepLearning.AI | Hrs |
|-----|-------------|-----------------|-----|
| 1 | ☐ Sección: S3 Introduction + Security | — | 2h |
| 2 | ☐ Sección: S3 Advanced (Replication, Storage Classes, Lifecycle) | — | 2h |
| 3 | ☐ Sección: RDS + Aurora + ElastiCache | — | 2.5h |
| 4 | ☐ Sección: DynamoDB | — | 1.5h |
| 5 | ☐ Sección: Other Databases (Redshift, Neptune, OpenSearch, etc.) | — | 1h |
| 6 | ☐ Repaso databases + quiz | — | 1h |
| 7 | ☐ Buffer / catch-up | — | 1h |

**Total: ~11 horas**  
**Enfocate en lo que NO usás día a día:** S3 Object Lock, Aurora Serverless v2, DAX, Global Tables.

---

### SEMANA 3 — Route 53, VPC, CloudFront, Global Accelerator

| Día | SAA (Maarek) | DeepLearning.AI | Hrs |
|-----|-------------|-----------------|-----|
| 1 | ☐ Sección: Route 53 (DNS, Routing Policies) | — | 2h |
| 2 | ☐ Sección: VPC Fundamentals + Advanced | — | 2.5h |
| 3 | ☐ Sección: VPC (NAT, NACL, VPC Peering, Endpoints, Flow Logs) | ☐ Building Agentic RAG with LlamaIndex (1h, gratis) | 3h |
| 4 | ☐ Sección: CloudFront + Global Accelerator | — | 1.5h |
| 5 | ☐ Sección: AWS Storage Extras (Snow Family, FSx, Storage Gateway) | — | 1.5h |
| 6 | ☐ Repaso networking + quiz | — | 1h |
| 7 | ☐ Buffer / catch-up | — | 1h |

**Total: ~12.5 horas**  
**Atención especial a:** Transit Gateway, PrivateLink, Direct Connect — son los temas de VPC donde más caen preguntas y que quizás no uses día a día.

---

### SEMANA 4 — Messaging (SQS, SNS, Kinesis), Containers, Serverless

| Día | SAA (Maarek) | DeepLearning.AI | Hrs |
|-----|-------------|-----------------|-----|
| 1 | ☐ Sección: SQS, SNS, Kinesis | — | 2h |
| 2 | ☐ Sección: Containers (ECS, Fargate, ECR, EKS) | — | 2h |
| 3 | ☐ Sección: Serverless (Lambda in depth) | — | 2h |
| 4 | ☐ Sección: Serverless (DynamoDB, API Gateway, Step Functions) | — | 1.5h |
| 5 | ☐ Sección: Serverless (Cognito, SAM) | ☐ AI Agentic Design Patterns with AutoGen (1h, gratis) | 2h |
| 6 | ☐ **PRACTICE EXAM #1** (65 preguntas, simular condiciones reales) | — | 2.5h |
| 7 | ☐ Revisión de respuestas incorrectas del Practice Exam #1 | — | 1.5h |

**Total: ~13.5 horas**  
**Milestone:** >75% en PE#1 = vas muy bien. <65% = intensificar semanas 5-6.

---

### SEMANA 5 — Security, Monitoring, Data Analytics, ML services

| Día | SAA (Maarek) | DeepLearning.AI | Hrs |
|-----|-------------|-----------------|-----|
| 1 | ☐ Sección: Security (KMS, SSM, Secrets Manager, ACM, WAF, Shield) | — | 2h |
| 2 | ☐ Sección: Security (GuardDuty, Inspector, Macie, Detective) | — | 1.5h |
| 3 | ☐ Sección: Monitoring (CloudWatch, CloudTrail, Config) | — | 2h |
| 4 | ☐ Sección: Data Analytics (Athena, Redshift, OpenSearch, EMR, Glue, QuickSight) | — | 2h |
| 5 | ☐ Sección: ML Services overview + Other Services | ☐ Functions, Tools and Agents with LangChain (1h, gratis) | 2h |
| 6 | ☐ Sección: AWS Organizations, Control Tower, Well-Architected | — | 1.5h |
| 7 | ☐ **PRACTICE EXAM #2** | — | 2.5h |

**Total: ~13.5 horas**  
**Security es el dominio con más peso (30%).** Dedicale atención extra a servicios que no uses día a día: WAF, Shield, Inspector, Macie.

---

### SEMANA 6 — Repaso intensivo + Practice Exams

| Día | SAA (Maarek) | DeepLearning.AI | Hrs |
|-----|-------------|-----------------|-----|
| 1 | ☐ Revisión de respuestas incorrectas del Practice Exam #2 | — | 2h |
| 2 | ☐ Repaso de servicios donde sacaste <70% | — | 2h |
| 3 | ☐ **PRACTICE EXAM #3** | ☐ Generative AI with LLMs (auditar módulo 1, si queda tiempo) | 3h |
| 4 | ☐ Revisión PE#3 + AWS Whitepapers (Well-Architected Framework) | — | 2h |
| 5 | ☐ **PRACTICE EXAM #4** | — | 2.5h |
| 6 | ☐ Revisión final — solo temas donde seguís fallando | — | 1.5h |
| 7 | ☐ Descanso activo: repasar cheat sheets, no estudiar material nuevo | — | 1h |

**Total: ~14 horas**  
**Milestone:** Consistentemente >80% en practice exams = listo para rendir. 75-80% = margen ajustado. <70% = reprogramar una semana.

---

### SEMANA 7 — Examen + cierre

| Día | SAA | DeepLearning.AI | Hrs |
|-----|-----|-----------------|-----|
| 1 | ☐ Repaso ligero — cheat sheets y servicios clave | — | 1h |
| 2 | ☐ Descanso. No estudiar. Dormir bien. | — | 0h |
| 3 | **☐ RENDIR EXAMEN SAA-C03** | — | 2.5h |
| 4-5 | — | ☐ Completar cursos DeepLearning.AI pendientes | 2h |

---

## Cursos DeepLearning.AI Intercalados

| Curso | Duración | Semana | Costo |
|-------|----------|--------|-------|
| ChatGPT Prompt Engineering for Developers | 1 hora | Semana 1 | Gratis |
| Building Agentic RAG with LlamaIndex | 1 hora | Semana 3 | Gratis |
| AI Agentic Design Patterns with AutoGen | 1 hora | Semana 4 | Gratis |
| Functions, Tools and Agents with LangChain | 1 hora | Semana 5 | Gratis |
| Generative AI with LLMs (auditar módulo 1) | 2-3 horas | Semana 6 | Gratis (audit) |

**Total: ~6-7 horas en 7 semanas** — ritmo manejable intercalado con la certificación principal.

---

## Métricas de Seguimiento

| Semana | Practice Exam | Target | Status |
|--------|--------------|--------|--------|
| 4 | PE #1 | >650/1000 | ☐ |
| 5 | PE #2 | >720/1000 | ☐ |
| 6 | PE #3 | >780/1000 | ☐ |
| 6 | PE #4 | >800/1000 | ☐ |

**Regla de decisión:** PE#3 > 780 → rendí en la fecha agendada. PE#3 < 700 → reprogramá 1 semana.

---

## Checklist Pre-Examen (día anterior)

- ☐ Dormiste 7+ horas
- ☐ Comiste bien, estás hidratado
- ☐ Si es online: software OnVUE instalado y testeado, habitación limpia, webcam/micrófono funcionando
- ☐ Si es presencial: sabés cómo llegar al testing center, documento de identidad listo
- ☐ Repasaste cheat sheet una última vez (no material nuevo)
- ☐ No estudiaste nada nuevo en las últimas 24 horas

---

## Presupuesto Total

| Item | Costo |
|------|-------|
| Examen SAA-C03 | $150 USD |
| Curso Maarek SAA (Udemy) | ~$15 USD |
| Practice Exams Maarek (Udemy) | ~$15 USD |
| Cursos DeepLearning.AI | $0 |
| **Total** | **$150 - $180 USD** |

---

## Después del Examen

1. Completar "Generative AI with LLMs" (3 semanas, $49/mes Coursera)
2. Preparar AWS AI Practitioner (AIF-C01) — apalancando lo aprendido en DeepLearning.AI
3. Comenzar preparación para Solutions Architect Professional — a ritmo más relajado

---

*Ejemplo real anonimizado — generado con el prompt de Career Repositioning.*  
*Los tiempos fueron calibrados para un profesional que ya usa AWS en producción diariamente.*
