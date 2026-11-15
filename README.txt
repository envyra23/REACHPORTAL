ENVYRA REACH — versión completa con autenticación revisada

1. Reemplazá tu reach.html por este archivo completo.
2. Abrilo desde Live Server (localhost), no desde file://.
3. Iniciá sesión con ENVYRA ID.
4. Si aparece un error, copiá el mensaje de Console/Network.

Proyecto Supabase: https://dgoemosdyuprdkxrivsc.supabase.co
La clave publishable del navegador es pública; no uses service_role/secret keys.

Nota: este archivo no se pudo probar contra tu proyecto Supabase en vivo. El código ahora verifica la sesión antes de consultar user_product_access, y evita hacer consultas dentro del callback de Auth. La política RLS sigue siendo necesaria y debe limitar la lectura al propio usuario.
