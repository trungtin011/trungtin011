<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Trang Cá Nhân</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            colors: { primary: "#6366f1", secondary: "#4f46e5" },
            borderRadius: {
              none: "0px",
              sm: "4px",
              DEFAULT: "8px",
              md: "12px",
              lg: "16px",
              xl: "20px",
              "2xl": "24px",
              "3xl": "32px",
              full: "9999px",
              button: "8px",
            },
          },
        },
      };
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css"
    />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/echarts/5.5.0/echarts.min.js"></script>
    <style>
      :where([class^="ri-"])::before { content: "\f3c2"; }
      body {
      background-color: #0f172a;
      color: #f8fafc;
      font-family: 'Inter', sans-serif;
      }
      .pixel-border {
      box-shadow: 0 0 0 2px #4c1d95;
      }
      .skill-badge {
      transition: transform 0.2s;
      }
      .skill-badge:hover {
      transform: translateY(-2px);
      }
      .github-stats {
      background: linear-gradient(145deg, rgba(30, 41, 59, 0.8), rgba(15, 23, 42, 0.8));
      backdrop-filter: blur(5px);
      }
      input[type="number"]::-webkit-inner-spin-button,
      input[type="number"]::-webkit-outer-spin-button {
      -webkit-appearance: none;
      margin: 0;
      }
    </style>
  </head>
  <body class="min-h-screen">
    <!-- Header Banner -->
    <header class="relative w-full h-80 overflow-hidden">
      <div
        class="absolute inset-0 bg-gradient-to-b from-indigo-900/70 to-blue-900/90 z-0"
      ></div>
      <div
        style="background-image: url('https://readdy.ai/api/search-image?query=retro%20pixel%20art%20gaming%20room%20with%20computer%20screens%2C%20game%20characters%2C%20mushrooms%2C%20and%20gaming%20items%20on%20shelves%2C%20dark%20blue%20background%20with%20neon%20accents%2C%208-bit%20style%20detailed%20pixel%20art&width=1280&height=400&seq=123456&orientation=landscape');"
        class="absolute inset-0 bg-cover bg-center opacity-80 z-0"
      ></div>
      <div class="relative z-10 flex flex-col h-full justify-end pb-4 px-6">
        <div class="flex justify-end">
          <div
            class="bg-slate-900/70 text-xs px-3 py-1 rounded-full text-slate-300"
          >
            <span>Lượt xem: 186</span>
          </div>
        </div>
      </div>
    </header>
    <!-- Main Content -->
    <main class="container mx-auto px-4 py-8 max-w-4xl">
      <!-- Introduction -->
      <section class="text-center mb-12">
        <h1
          class="text-3xl font-bold mb-4 flex items-center justify-center gap-2"
        >
          <span class="text-2xl">👋</span> Xin chào, tôi là Nguyễn Trung Tín
        </h1>
        <p class="text-lg text-indigo-300 mb-4">(TinMagicDEV)</p>
        <!-- Social Links -->
        <div class="flex justify-center gap-3 mb-6">
          <a
            href="https://github.com/TinMagicDEV"
            class="flex items-center gap-2 bg-gray-800 hover:bg-gray-700 text-white px-4 py-2 rounded-button transition-colors"
          >
            <div class="w-5 h-5 flex items-center justify-center">
              <i class="ri-github-fill"></i>
            </div>
            <span>GitHub</span>
          </a>
          <a
            href="#"
            class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-button transition-colors"
          >
            <div class="w-5 h-5 flex items-center justify-center">
              <i class="ri-facebook-fill"></i>
            </div>
            <span>Facebook</span>
          </a>
        </div>
        <!-- Bio -->
        <div class="bg-slate-800/50 p-6 rounded-lg max-w-2xl mx-auto">
          <p class="text-lg mb-2">
            <span
              class="inline-flex items-center justify-center w-6 h-6 mr-2 bg-primary rounded-full"
            >
              <i class="ri-code-s-slash-line text-white"></i>
            </span>
            Lập trình viên fullstack đam mê, tạo ra các ứng dụng web mạnh mẽ và
            có khả năng mở rộng.
          </p>
          <p class="text-slate-300">
            Thành thạo cả công nghệ front-end và back-end, với khả năng tối ưu
            hóa trải nghiệm người dùng và hiệu suất.
          </p>
        </div>
      </section>
      <!-- Skills -->
      <section class="mb-12">
        <h2 class="text-2xl font-bold mb-6 flex items-center">
          <div
            class="w-8 h-8 flex items-center justify-center mr-2 bg-indigo-600 rounded-lg"
          >
            <i class="ri-tools-fill text-white"></i>
          </div>
          Kỹ Năng
        </h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-3">
          <div
            class="skill-badge bg-red-600 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-laravel-fill"></i>
            </div>
            <span>Laravel</span>
          </div>
          <div
            class="skill-badge bg-indigo-600 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-php-line"></i>
            </div>
            <span>PHP</span>
          </div>
          <div
            class="skill-badge bg-yellow-500 text-black px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-javascript-line"></i>
            </div>
            <span>JavaScript</span>
          </div>
          <div
            class="skill-badge bg-green-600 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-vuejs-line"></i>
            </div>
            <span>Vue.js</span>
          </div>
          <div
            class="skill-badge bg-cyan-500 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-css3-line"></i>
            </div>
            <span>Tailwind CSS</span>
          </div>
          <div
            class="skill-badge bg-purple-600 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-bootstrap-fill"></i>
            </div>
            <span>Bootstrap</span>
          </div>
          <div
            class="skill-badge bg-blue-600 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-database-2-line"></i>
            </div>
            <span>MySQL</span>
          </div>
          <div
            class="skill-badge bg-blue-400 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-docker-fill"></i>
            </div>
            <span>Docker</span>
          </div>
          <div
            class="skill-badge bg-blue-800 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-visual-studio-line"></i>
            </div>
            <span>VS Code</span>
          </div>
          <div
            class="skill-badge bg-orange-500 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-mail-send-line"></i>
            </div>
            <span>Postman</span>
          </div>
          <div
            class="skill-badge bg-red-500 text-white px-4 py-2 rounded-lg flex items-center gap-2"
          >
            <div class="w-6 h-6 flex items-center justify-center">
              <i class="ri-pen-nib-line"></i>
            </div>
            <span>Figma</span>
          </div>
        </div>
      </section>
      <!-- GitHub Stats -->
      <section class="mb-12">
        <h2 class="text-2xl font-bold mb-6 flex items-center">
          <div
            class="w-8 h-8 flex items-center justify-center mr-2 bg-indigo-600 rounded-lg"
          >
            <i class="ri-github-fill text-white"></i>
          </div>
          Thống kê GitHub
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <!-- Stats -->
          <div class="github-stats p-6 rounded-lg">
            <h3 class="text-xl font-semibold mb-4 text-indigo-300">
              TinMagicDEV's GitHub Stats
            </h3>
            <div class="space-y-3">
              <div class="flex justify-between">
                <span class="text-slate-300">Tổng số Star:</span>
                <span class="font-mono font-bold">0</span>
              </div>
              <div class="flex justify-between">
                <span class="text-slate-300">Tổng số Commit (2023):</span>
                <span class="font-mono font-bold">274</span>
              </div>
              <div class="flex justify-between">
                <span class="text-slate-300">Tổng số PR:</span>
                <span class="font-mono font-bold">15</span>
              </div>
              <div class="flex justify-between">
                <span class="text-slate-300">Tổng số Issues:</span>
                <span class="font-mono font-bold">0</span>
              </div>
              <div class="flex justify-between">
                <span class="text-slate-300">Đóng góp (năm qua):</span>
                <span class="font-mono font-bold">0</span>
              </div>
            </div>
            <div class="mt-4 flex justify-center">
              <div
                class="w-24 h-24 rounded-full bg-slate-700 flex items-center justify-center text-2xl font-bold"
              >
                C+
              </div>
            </div>
          </div>
          <!-- Languages -->
          <div class="github-stats p-6 rounded-lg">
            <h3 class="text-xl font-semibold mb-4 text-indigo-300">
              Ngôn ngữ sử dụng nhiều nhất
            </h3>
            <div id="languagesChart" class="w-full h-64"></div>
          </div>
        </div>
      </section>
      <!-- Support Me -->
      <section class="text-center">
        <h2 class="text-2xl font-bold mb-6">Hỗ trợ tôi</h2>
        <a
          href="#"
          class="inline-flex items-center gap-2 bg-yellow-500 hover:bg-yellow-600 text-black font-bold px-6 py-3 rounded-button transition-colors"
        >
          <div class="w-6 h-6 flex items-center justify-center">
            <i class="ri-cup-line"></i>
          </div>
          <span>Mua cho tôi một ly cà phê</span>
        </a>
      </section>
    </main>
    <!-- Footer -->
    <footer class="mt-16 py-6 bg-slate-900">
      <div class="container mx-auto px-4 text-center text-slate-400">
        <p>© 2025 Nguyễn Trung Tín (TinMagicDEV). Đã đăng ký bản quyền.</p>
        <p class="mt-2 text-sm">Cập nhật lần cuối: 18/05/2025</p>
      </div>
    </footer>
    <script>
      document.addEventListener("DOMContentLoaded", function () {
        // Languages Chart
        const languagesChart = echarts.init(
          document.getElementById("languagesChart"),
        );
        const option = {
          animation: false,
          tooltip: {
            trigger: "item",
            backgroundColor: "rgba(255, 255, 255, 0.8)",
            textStyle: {
              color: "#1f2937",
            },
          },
          color: [
            "rgba(87, 181, 231, 1)",
            "rgba(141, 211, 199, 1)",
            "rgba(251, 191, 114, 1)",
            "rgba(252, 141, 98, 1)",
          ],
          series: [
            {
              name: "Ngôn ngữ",
              type: "pie",
              radius: "70%",
              center: ["50%", "50%"],
              data: [
                { value: 39.48, name: "Blade" },
                { value: 32.24, name: "PHP" },
                { value: 24.2, name: "HTML" },
                { value: 1.55, name: "CSS" },
                { value: 1.1, name: "JavaScript" },
                { value: 0.93, name: "Vue" },
              ],
              emphasis: {
                itemStyle: {
                  shadowBlur: 10,
                  shadowOffsetX: 0,
                  shadowColor: "rgba(0, 0, 0, 0.5)",
                },
              },
              label: {
                color: "#f8fafc",
                formatter: "{b}: {d}%",
              },
            },
          ],
        };
        languagesChart.setOption(option);
        // Responsive chart
        window.addEventListener("resize", function () {
          languagesChart.resize();
        });
      });
    </script>
  </body>
</html>
