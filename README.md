- 👋 Hi, I’m **MD. Shariar Hossain Sun**
- 👀 I’m interested in programming...
- 🌱 I’m currently learning web development using HTML, CSS and JavaScript...
- 💞️ I’m looking to collaborate on software development using C/C++....
- 📫 How to reach me -> using my linkedin account link  **[MD. Shariar Hossain Sun](https://www.linkedin.com/in/md-shariar-hossain-sun-aa77621ab/)**...


![](https://raw.githubusercontent.com/MDShariarHossainSun/Codeforces-Stats/main/output/light_card.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/MDShariarHossainSun/Codeforces-Stats/main/output/light_card.svg)


![](https://raw.githubusercontent.com/MDShariarHossainSun/Codeforces-Stats/main/output/max_rating.svg)
![](https://raw.githubusercontent.com/MDShariarHossainSun/Codeforces-Stats/main/output/rating.svg)

<!---
MDShariarHossainSun/MDShariarHossainSun is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 // ANSWER CHART
    context = $('#answer-chart').get(0).getContext('2d');

    data = [
        {
            /* Accepted */
            value: 312,
            color: '#27AE60',
            highlight: '#2CC36B',
            label: 'Accepted'
        },
        {
            /* Compilation Error */
            value: 43,
            color: '#F1C40F',
            highlight: '#F2CA27',
            label: 'Compilation error'
        },
        {
            /* Runtime Error */
            value: 29,
            color: '#00AAAA',
            highlight: '#20CBCB',
            label: 'Runtime error'
        },
        {
            /* Time Limit Exceeded */
            value: 13,
            color: '#2980B9',
            highlight: '#2E8ECE',
            label: 'Time limit exceeded'
        },
        {
            /* Presentation Error */
            value: 45,
            color: '#86862C',
            highlight: '#9A9A41',
            label: 'Presentation error'
        },
        {
            /* Wrong Answer */
            value: 287,
            color: '#E74C3C',
            highlight: '#FF5A5E',
            label: 'Wrong answer'
        },
        {
            /* Possible Runtime Error */
            value: 0,
            color: '#8E44AD',
            highlight: '#9B59B6',
            label: 'Possible runtime error'
        },
        {
            /* Memory Limit Exceeded */
            value: 0,
            color: '#FF9800',
            highlight: '#F1A12C',
            label: 'Memory limit exceeded'
        }
    ];

    options = {
        // Number - The percentage of the chart that we cut out of the middle
        percentageInnerCutout : 60,

        scaleFontSize: 10,
        // Number - Amount of animation steps
        animationSteps : 100,
        // String - Animation easing effect
        animationEasing : "easeInOutCirc",
        // Boolean - Whether we animate the rotation of the Doughnut
        animateRotate : true,
        // Boolean - Whether we animate scaling the Doughnut from the centre
        animateScale : false,
        // Number - Tooltip label font size in pixels
        tooltipFontSize: 10,
        // String - A legend template
        legendTemplate : "<ul class=\"<%=name.toLowerCase()%>-legend\"><% for (var i=0; i<segments.length; i++){%><li><span style=\"background-color:<%=segments[i].fillColor%>\"></span><%if(segments[i].label){%><%=segments[i].label%><%}%></li><%}%></ul>"
    };

    chart = new Chart(context).Doughnut(data, options);

    $('#answer-legend').html(chart.generateLegend());

    // LANGUAGE CHART
    context = $('#language-chart').get(0).getContext('2d');
    data = [
        {
            /* C */
            value: 430,
            color: '#3498db',
            highlight: '#3498db',
            label: 'C'
        },
        {
            /* C++ */
            value: 230,
            color: '#2980b9',
            highlight: '#2980b9',
            label: 'C++'
        },
        {
            /* C# */
            value: 0,
            color: '#e67e22',
            highlight: '#e67e22',
            label: 'C#'
        },
        {
            /* Java */
            value: 1,
            color: '#e74c3c',
            highlight: '#e74c3c',
            label: 'Java'
        },
        {
            /* Ruby */
            value: 0,
            color: '#c0392b',
            highlight: '#c0392b',
            label: 'Ruby'
        },
        {
            /* Python */
            value: 0,
            color: '#9b59b6',
            highlight: '#9b59b6',
            label: 'Python'
        },
        {
            /* Scala */
            value: 0,
            color: '#c02b42',
            highlight: '#c02b42',
            label: 'Scala'
        },
        {
            /* Lua */
            value: 0,
            color: '#4a48d6',
            highlight: '#4a48d6',
            label: 'Lua'
        },
        {
            /* Javascript */
            value: 1,
            color: '#7d9e42',
            highlight: '#7d9e42',
            label: 'Javascript'
        },
        {
            /* Go */
            value: 0,
            color: '#34d0db',
            highlight: '#34d0db',
            label: 'Go'
        },
        {
            /* PostgreSQL */
            value: 67,
            color: '#1a6199',
            highlight: '#1a6199',
            label: 'SQL'
        },
        {
            /* Dart */
            value: 0,
            color: '#4b6cca',
            highlight: '#4b6cca',
            label: 'Dart'
        },
        {
            /* Kotlin */
            value: 0,
            color: '#f97603',
            highlight: '#f97603',
            label: 'Kotlin'
        },
        {
            /* Haskell */
            value: 0,
            color: '#4a4996',
            highlight: '#4a4996',
            label: 'Haskell'
        },
        {
            /* Ocaml */
            value: 0,
            color: '#b17a4d',
            highlight: '#b17a4d',
            label: 'Ocaml'
        },
        {
            /* Pascal */
            value: 0,
            color: '#ed7084',
            highlight: '#ed7084',
            label: 'Pascal'
        },
        {
            /* R */
            value: 0,
            color: '#8697BF',
            highlight: '#8697BF',
            label: 'R'
        },
        {
            /* PHP */
            value: 0,
            color: '#8892BF',
            highlight: '#8892BF',
            label: 'PHP'
        },
        {
            /* Clojure */
            value: 0,
            color: '#91DB47',
            highlight: '#91DB47',
            label: 'Clojure'
        },
        {
            /* Rust */
            value: 0,
            color: '#505f67',
            highlight: '#505f67',
            label: 'Rust'
        },
        // Liberar comentados quando estiverem disponíveis para produção
        {
            /* Swift */
            value: 0,
            color: '#FA613F',
            highlight: '#FA613F',
            label: 'Swift'
        },
        // {
        //     /* TypeScript */
        //     value: ,
        //     color: '#ed7084',
        //     highlight: '#ed7084',
        //     label: 'TypeScript'
        // },
        // {
        //     /* Julia */
        //     value: ,
        //     color: '#ed7084',
        //     highlight: '#ed7084',
        //     label: 'Julia'
        // },
        {
            /* Elixir */
            value: 0,
            color: '#e84d50',
            highlight: '#e84d50',
            label: 'Elixir'
        },
    ];

    options = {
        // Number - The percentage of the chart that we cut out of the middle
        percentageInnerCutout : 60,
        scaleFontSize: 10,
        // Number - Amount of animation steps
        animationSteps : 100,
        // String - Animation easing effect
        animationEasing : "easeInOutCirc",
        // Boolean - Whether we animate the rotation of the Doughnut
        animateRotate : true,
        // Boolean - Whether we animate scaling the Doughnut from the centre
        animateScale : false,
        // Number - Tooltip label font size in pixels
        tooltipFontSize: 10,
        legend: {
            display: false,
        },
        // String - A legend template
        legendTemplate : "<ul class=\"<%=name.toLowerCase()%>-legend\"><% for (var i=0; i<segments.length; i++){%><li><span style=\"background-color:<%=segments[i].fillColor%>\"></span><%if(segments[i].label){%><%=segments[i].label%><%}%></li><%}%></ul>"
    };

    chart = new Chart(context).Doughnut(data, options);
});
