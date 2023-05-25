<!DOCTYPE html>
<html>
<head>
    <title>Diagrama de Clash Royale</title>
    <script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
    <script>
        mermaid.initialize({ startOnLoad: true });
    </script>
</head>
<body>
    <div class="mermaid">
        graph TB
        inicio((Inicio))
        arena[Arena]
        t1[T1]
        t2[T2]
        k1[K1]
        k2[K2]
        k3[K3]
        k4[K4]
        fin((Fin))

        inicio --> arena
        arena --> t1
        arena --> t2
        t1 --> k1
        t2 --> k2
        t2 --> k3
        t2 --> k4
        k1 --> fin
        k2 --> fin
        k3 --> fin
        k4 --> fin
    </div>
</body>
</html>
