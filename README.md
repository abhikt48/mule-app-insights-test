# mule-app-insights-test
Codeless Agent test with Mule 4 HTTP endpoin

# Steps for publish logs to APP Insight
1. Update connection [applicationinsights.json](https://github.com/abhikt48/mule-app-insights-test/blob/main/app-insights-agent/applicationinsights.json)
2. Dowload and copy `applicationinsights-agent-3.5.4.jar` in app-insights-agentfolder
3. Import application in Anypoint Studio
4. Run application with with VM argument `-javaagent:"***\agent\applicationinsights-agent-3.5.2.jar" `
5. Access URL - http://localhost:8081/ai/2
6. Check dependency Tree in AI
