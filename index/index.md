---
layout: home
title: "Bienvenido a mi Portafolio"
---

# 👋 Hola, soy Sergio Polo García

Soy un desarrollador de software con más de 2 años de experiencia en C# y .NET. Me apasiona crear aplicaciones eficientes y escalables, y estoy continuamente aprendiendo nuevas tecnologías para mejorar mis habilidades.

## Mis Intereses
- Desarrollo en C# y .NET
- Arquitectura de software
- Mercados financieros y trading algorítmico
- Tecnología deportiva y seguimiento de rendimiento

## Contacto
- 📧 [sergio.polo@example.com](mailto:sergio.polo@example.com)
- [LinkedIn](https://www.linkedin.com/in/sergiopologarcia)



## Mis Lenguajes de Programación

<canvas id="langChart" width="400" height="200"></canvas>

<script>
    var ctx = document.getElementById('langChart').getContext('2d');
    var langChart = new Chart(ctx, {
        type: 'bar',
        data: {
            labels: ['C#', 'JavaScript', 'SQL'],
            datasets: [{
                label: '# de Repositorios',
                data: [10, 5, 3], // Reemplaza con tus datos reales
                backgroundColor: [
                    'rgba(54, 162, 235, 0.2)',
                    'rgba(255, 206, 86, 0.2)',
                    'rgba(75, 192, 192, 0.2)'
                ],
                borderColor: [
                    'rgba(54, 162, 235, 1)',
                    'rgba(255, 206, 86, 1)',
                    'rgba(75, 192, 192, 1)'
                ],
                borderWidth: 1
            }]
        },
        options: {
            scales: {
                y: {
                    beginAtZero: true
                }
            }
        }
    });
</script>
