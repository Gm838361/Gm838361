ScriptEngineManager mgr = new ScriptEngineManager();
ScriptEngine engine = mgr.getEngineByName("javascript");
Bindings bindings = engine.getBindings(ScriptContext.ENGINE_SCOPE);
console.log(helloworld')'

