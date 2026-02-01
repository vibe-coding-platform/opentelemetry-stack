# opentelemetry-stack
OpenTelemetry templates + SLO dashboards + trace-driven alerts.
🚀 PRODUCTION STACK TEMPLATES LIVE
https://github.com/vibe-coding-platform/opentelemetry-stack

✅ OpenTelemetry Templates → Auto-instrumented  
✅ SLO Dashboards → 1-click Grafana import  
✅ Trace-Driven Alerts → Pre-configured rules  

DEPLOY IN 5 MINUTES:

1. Clone: platform-starter + OpenTelemetry templates
2. docker-compose up → Collector + Grafana + Tempo  
3. Import SLO dashboard → Live traces/metrics  
4. Alerts fire → MTTR <3min guaranteed

# OpenTelemetry Production Stack 🚀

## 5-Minute Production Observability

```bash
git clone https://github.com/vibe-coding-platform/platform-starter
cd platform-starter
# Copy observability files from opentelemetry-stack
docker-compose -f docker-compose.observability.yml up -d
