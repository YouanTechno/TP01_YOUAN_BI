"# TP01_YOUAN_BI" 
méthodes supportées par la servlet:
HttpServlet();
doGet(HttpServletRequest req, HttpServletResponse resp);
getLastModified(HttpServletRequest req);
doHead(HttpServletRequest req, HttpServletResponse resp);
doPost(HttpServletRequest req, HttpServletResponse resp);
doDelete(HttpServletRequest req, HttpServletResponse resp);
getAllDeclaredMethods(Class<? extends HttpServlet> c);
doOptions(HttpServletRequest req, HttpServletResponse resp);
doTrace(HttpServletRequest req, HttpServletResponse resp);
service(HttpServletRequest req, HttpServletResponse resp);
maybeSetLastModified(HttpServletResponse resp, long lastModified);
service(ServletRequest req, ServletResponse res);