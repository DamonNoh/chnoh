<html lang="ko" class="transition-colors duration-300">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>포트폴리오</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['Poppins', 'sans-serif'],
          },
        },
      },
    }
  </script>
  <script>
    function toggleDarkMode() {
      document.documentElement.classList.toggle('dark');
      localStorage.setItem('theme', document.documentElement.classList.contains('dark') ? 'dark' : 'light');
    }
    if (localStorage.getItem('theme') === 'dark') {
      document.documentElement.classList.add('dark');
    }
  </script>
<style>
  .fade-in {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease-out, transform 0.6s ease-out;
  }
  .fade-in.visible {
    opacity: 1;
    transform: none;
  }
</style>
<script>
  document.addEventListener('DOMContentLoaded', function () {
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    }, { threshold: 0.1 });

    document.querySelectorAll('.fade-in').forEach(el => {
      observer.observe(el);
    });
  });
   document.documentElement.classList.add('dark');
  if (localStorage.getItem('theme') === 'light') {
    document.documentElement.classList.remove('dark');
  }
</script>
<body class="text-sm font-poppins bg-white text-gray-800 dark:bg-gray-900 dark:text-gray-100 transition-colors duration-300">
  <!-- Header -->
  <header class="relative bg-cover bg-center text-white" style="background-image: url('https://images.unsplash.com/photo-1626379953822-baec19c3accd?q=80&w=1740&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');">
    <div class="bg-black bg-opacity-50">
      <div class="max-w-5xl mx-auto px-6 py-8 flex justify-between items-center text-left">
      <h1 class="text-2xl font-bold tracking-tight text-left">미래기술 기획 기반 제너럴리스트, <br>노충현</br></h1>
      <div class="space-x-3 flex items-center">
        <button onclick="toggleDarkMode()" class="text-gray-600 dark:text-gray-300 hover:text-blue-500 text-xl">🌓</button>
        <a href="resume.pdf" download class="text-sm bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-full shadow">이력서 다운로드</a>
      </div>
    </div>
    <nav class="max-w-5xl mx-auto px-6 py-2">
      <ul class="flex flex-wrap gap-4 text-sm text-gray-600 dark:text-gray-300">
        <li><a href="#strengths" class="hover:text-blue-500">Core Competencies</a></li>
        <li><a href="#about" class="hover:text-blue-500">About Me</a></li>
        <li><a href="#education" class="hover:text-blue-500">Education</a></li>
        <li><a href="#projects" class="hover:text-blue-500">Projects</a></li>
        <li><a href="#skills" class="hover:text-blue-500">Skills</a></li>
        <li><a href="#gallery" class="hover:text-blue-500">Work Gallery</a></li>
      </ul>
    </nav>
  </div>
  </header>

  <script>
  document.documentElement.classList.add('dark');
  if (localStorage.getItem('theme') === 'light') {
    document.documentElement.classList.remove('dark');
  }
</script>

  <!-- Main Content -->
  <main class="max-w-5xl mx-auto px-6 space-y-24">
    <section id="strengths" class="fade-in py-16 border-b border-gray-200 dark:border-gray-700">
      <h2 class="text-2xl font-semibold mb-6">💪🏻Core Competencies</h2>
      <ul class="list-disc pl-6 space-y-2 text-base">
        <li>사업기획 및 B2B, B2G 제안, 홍보/마케팅, 소재 제작 등 다양한 업무스코프 경험 및 빠른 적응</li>
        <li>프로젝트 기획, 총괄 관리 및 운영 역량 보유</li>
        <li>콘텐츠 프로덕트 론칭에 따른 글로벌 홍보·마케팅 실행 경험 보유</li>
        <li>C-Level 의사결정을 위한 XR, 실감콘텐츠 등 기술 산업 트렌드 분석 및 사업 전략 제안</li>
        <li>대행사 및 외부 파트너 커뮤니케이션 관리 역량</li>
      </ul>
    </section>

    <section id="about" class="fade-in py-16 border-b border-gray-200 dark:border-gray-700">
      <h2 class="text-2xl font-semibold mb-6">🧑🏻‍💼About Me</h2>
      <p class="leading-relaxed text-base">
        홍익대 광고홍보대학원에서 뉴미디어콘텐츠를 전공했습니다. 2010년부터 미디어 콘텐츠 기획, 제안 및 제작 PM으로 다양한 실무 경험을 쌓아왔으며 콘텐츠 기획부터 사업 기획, 디지털 홍보 전략에 이르기까지 창의적인 아이디어와 책임감을 바탕으로 기업 및 제품의 가치를 효과적으로 전달하는 데 집중해 왔습니다. 스코넥엔터테인먼트에서 PD로 재직하며 XR사업본부 소속으로 XR 기술산업 트렌드를 리서치, 이를 기반으로 한 사업 전략 강화와 함께 관련 신규 콘텐츠 기획 및 마케팅 전략 수립에 기여하였습니다. 
      </p>
    </section>

    <section id="education" class="fade-in py-16 border-b border-gray-200 dark:border-gray-700 leading-snug">
      <h2 class="text-2xl font-semibold mb-6">🎓Education</h2>
      <ul class="space-y-2 text-base leading-tight">
        <li><strong>고등학교</strong>｜ 인천남고등학교｜ 1999.03-2002.02</li>
        <li><strong>대학교</strong>｜ 원광대학교 인문학부 고고미술사학 전공｜ 2002.03-2010.08</li>
        <li><strong>대학원</strong>｜ 홍익대학교 광고홍보대학원 뉴미디어콘텐츠전공｜ 2014.03-2017.08</li>
      <div class="mt-2 ml-0 text-xs text-gray-600 dark:text-gray-300">
  <div class="flex items-center flex-wrap gap-2">
    <span class="font-semibold">📖학위논문</span>
    <span class="text-sm">브랜드스토어의 VR마케팅이 브랜드태도 및 구매의도에 미치는 영향: Burnd H. Schmitt의 체험이론을 중심으로 </span>
    <a href="https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE10770291" target="_blank" class="inline-block px-3 py-1 text-xs font-semibold text-white bg-blue-600 rounded hover:bg-blue-700 transition">View</a>
  </div>
</div>
  </ul>
      </ul>
    </section>

</details>
    <section id="projects" class="fade-in py-16 border-b border-gray-200 dark:border-gray-700">
  <h2 class="text-2xl font-semibold mb-6">💻Projects</h2>
  <div class="space-y-4">
    <!-- 회사별 드롭다운 -->
        <details open class="text-sm bg-white dark:bg-gray-800 rounded-lg shadow p-4">
          <summary class="cursor-pointer text-sm font-semibold">SKONEC ENTERTAINMENT｜XR사업본부·차장｜2022.03-Current</summary>
          <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/3216330/ss_62f95625f12fb402530f208d0a77fdcef8368456.1920x1080.jpg?t=1737697230" alt="Another Door Thumbnail" onclick="openPopup(['https://www.youtube.com/embed/B3R3sP5ojlA'])" style="cursor: pointer;" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">VR Horror Puzzle, 'Another Door: Escape Room'<br>출시 마케팅(2024)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">
<strong>👉🏻 R&R</strong>
<li>마케팅 채널 발굴 및 기획, 미디어믹스</li>
<li>소셜미디어 채널(Facebook, Youtube, Instagram, X 등) 콘텐츠 기획 및 운영</li>
<li>브랜드 웹사이트, 디스코드 구축, CRM 커뮤니케이션 지원</li>
<li>보도자료, 광고 카피라이트 등 크리에이티브 기획, 제작/관리</li>
<li>스토어 대시보드 운영관리, 지표 분석 및 리포팅</li>
<li>KOCCA 독일 Gamescom 2024, 일본 TGS 한국공동관 참가, 현장 운영 리드</li>
<strong>👍🏻 RESULT</strong>
<li>앱 노출 1,900K 확보, 구매 유저 62% 타겟 지역인 북미, 영국에서 발생 (출시 후, 3개월)</li>
<li>신규 유저 확보를 위한 스토어 크리에이티브 A/B테스트를 통해 전환율 37.5% 개선</li>
<li>Meta Horizon Store, Puzzle of the Year 2024 선정</li>
<li>공식 홈페이지 한국인터넷전문가협회 i-AWARDS 2024 문화/관광 부문 대상 수상</li><br>
            <a href=https://www.meta.com/experiences/7941437402579936/>Meta Horizon Store →</a><br>
            <a href=https://store.steampowered.com/app/3216330/Another_Door_Escape_Room/>Steam Store →</a><br>
          </div>
        </div>
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="https://scontent-ssn1-1.oculuscdn.com/v/t64.5771-25/38974676_3959964027648739_2258453843695372064_n.jpg?stp=dst-jpg_q92_s1440x1440_tt6&_nc_cat=104&ccb=1-7&_nc_sid=6e7a0a&_nc_ohc=6WJeBaSVi1UQ7kNvwF0gjHO&_nc_oc=AdmgRtgEGhcmy2S2TdORm3mQQIkO96DdGEtgbmtcro_K2VLmGJ28esFKldshYEpJhm0&_nc_zt=3&_nc_ht=scontent-ssn1-1.oculuscdn.com&oh=00_AfMTZsUH7G2lCebV67f2ncE4Au0IHotWTMAUig3mo5_hDg&oe=686470C0" alt="Strike Rush Thumbnail" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">VR PVP Arena Shooter, 'Strike Rush'<br>출시 마케팅(2024)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">
<strong>👉🏻 R&R</strong>
<li>마케팅 채널 발굴 및 기획, 미디어믹스</li>
<li>소셜미디어 채널(Facebook, Youtube, Instagram, X 등) 콘텐츠 기획 및 운영</li>
<li>브랜드 웹사이트, 디스코드 구축, CRM 커뮤니케이션 지원</li>
<li>보도자료, 광고 카피라이트 등 크리에이티브 기획, 제작/관리</li>
<li>스토어 대시보드 운영관리, 지표 분석 및 리포팅</li>
<strong>👍🏻 RESULT</strong>
<li>Reach to conversion 7.0% (출시 후, 3개월)</li>
<li>신규 유저 확보를 위한 스토어 크리에이티브 A/B테스트를 통해 전환율 27.3% 개선</li>
<li>영미권 KOL 캠페인 + Press Release Total Impression 600K 확보, 국가 별 액티브유저 62% 북미,영국에서 발생 (출시 후, 3개월)</li>
<li>UA 캠페인을 통해 디스코드 서버 멤버 4.5K 확보</li>
<li>한국콘텐츠진흥원 게임더하기 2024 지원 수혜게임 참가신청서 작성 및 피칭(선정)</li><br>
            </p>
            <a href=https://www.meta.com/experiences/7224231090949496/>Meta Horizon Store →</a>
          </div>
        </div>
      </div>
    </details>

    <details class="text-sm bg-white dark:bg-gray-800 rounded-lg shadow p-4">
      <summary class="cursor-pointer text-sm font-semibold">GIANTSTEP｜뉴미디어사업본부 · 팀장｜2019.08-2021.09</summary>
      <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail2.jpg" alt="Mr. TRAVELER 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">인천국제공항 T1밀레니엄홀 미디어타워 영상제작(2021)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">혼합현실 보드게임, 전 세계 여행을 테마로 한 인터랙티브 플레이 경험을 제공. Meta Quest 3를 기반으로 공간 매핑과 핸드트래킹을 활용.</p>
          </div>
        </div>
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail1.jpg" alt="Dr. POP 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">5G 실감콘텐츠 기획홍보 및 시연콘텐츠 제작운영,'광화시대'(2021)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">VR 척추교정 시뮬레이션 게임. 유머와 아이러니를 결합한 블랙코미디 연출로 캐릭터의 목을 "팝"하며 진행되는 캐주얼 체험형 콘텐츠.</p>
          </div>
        </div>
        <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail2.jpg" alt="Mr. TRAVELER 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">광주 전일빌딩245 몰입형 영상관 구축(2020)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">혼합현실 보드게임, 전 세계 여행을 테마로 한 인터랙티브 플레이 경험을 제공. Meta Quest 3를 기반으로 공간 매핑과 핸드트래킹을 활용.</p>
          </div>
        </div>
          <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail2.jpg" alt="Mr. TRAVELER 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">기술특례상장(2020)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">혼합현실 보드게임, 전 세계 여행을 테마로 한 인터랙티브 플레이 경험을 제공. Meta Quest 3를 기반으로 공간 매핑과 핸드트래킹을 활용.</p>
          </div>
        </div>
      </div>
    </details>

        <details class="text-sm bg-white dark:bg-gray-800 rounded-lg shadow p-4">
      <summary class="cursor-pointer text-sm font-semibold">REDROVER｜첨단영상사업부·차장｜2016.03-2019.08</summary>
      <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail2.jpg" alt="Mr. TRAVELER 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Mr. TRAVELER (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">혼합현실 보드게임, 전 세계 여행을 테마로 한 인터랙티브 플레이 경험을 제공. Meta Quest 3를 기반으로 공간 매핑과 핸드트래킹을 활용.</p>
          </div>
        </div>
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail1.jpg" alt="Dr. POP 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Dr. POP (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">VR 척추교정 시뮬레이션 게임. 유머와 아이러니를 결합한 블랙코미디 연출로 캐릭터의 목을 "팝"하며 진행되는 캐주얼 체험형 콘텐츠.</p>
          </div>
        </div>
      </div>
    </details>

        <details class="text-sm bg-white dark:bg-gray-800 rounded-lg shadow p-4">
      <summary class="cursor-pointer text-sm font-semibold">MEDIAFRONT｜기획/PM팀·대리｜2014.11-2016.03</summary>
      <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail2.jpg" alt="Mr. TRAVELER 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Mr. TRAVELER (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">혼합현실 보드게임, 전 세계 여행을 테마로 한 인터랙티브 플레이 경험을 제공. Meta Quest 3를 기반으로 공간 매핑과 핸드트래킹을 활용.</p>
          </div>
        </div>
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail1.jpg" alt="Dr. POP 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Dr. POP (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">VR 척추교정 시뮬레이션 게임. 유머와 아이러니를 결합한 블랙코미디 연출로 캐릭터의 목을 "팝"하며 진행되는 캐주얼 체험형 콘텐츠.</p>
          </div>
        </div>
      </div>
    </details>

        <details class="text-sm bg-white dark:bg-gray-800 rounded-lg shadow p-4">
      <summary class="cursor-pointer text-sm font-semibold">BIG-I ENTERTAINMENT｜사업기획팀·대리｜2012.10-2014.05</summary>
      <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail2.jpg" alt="Mr. TRAVELER 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Mr. TRAVELER (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">혼합현실 보드게임, 전 세계 여행을 테마로 한 인터랙티브 플레이 경험을 제공. Meta Quest 3를 기반으로 공간 매핑과 핸드트래킹을 활용.</p>
          </div>
        </div>
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail1.jpg" alt="Dr. POP 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Dr. POP (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">VR 척추교정 시뮬레이션 게임. 유머와 아이러니를 결합한 블랙코미디 연출로 캐릭터의 목을 "팝"하며 진행되는 캐주얼 체험형 콘텐츠.</p>
          </div>
        </div>
      </div>
    </details>

        <details class="text-sm bg-white dark:bg-gray-800 rounded-lg shadow p-4">
      <summary class="cursor-pointer text-sm font-semibold">MEDIASPACE｜기획팀·주임｜2010.04-2012.10</summary>
      <div class="mt-4 space-y-6">
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail2.jpg" alt="Mr. TRAVELER 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Mr. TRAVELER (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">혼합현실 보드게임, 전 세계 여행을 테마로 한 인터랙티브 플레이 경험을 제공. Meta Quest 3를 기반으로 공간 매핑과 핸드트래킹을 활용.</p>
          </div>
        </div>
        <div class="flex flex-col md:flex-row items-start gap-6 bg-gray-50 dark:bg-gray-900 rounded-lg p-4">
          <img src="thumbnail1.jpg" alt="Dr. POP 썸네일" class="w-full md:w-1/3 rounded-lg object-cover h-48">
          <div class="flex-1">
            <h3 class="text-xl font-semibold mb-2">Dr. POP (2025)</h3>
            <p class="text-sm text-gray-700 dark:text-gray-300">VR 척추교정 시뮬레이션 게임. 유머와 아이러니를 결합한 블랙코미디 연출로 캐릭터의 목을 "팝"하며 진행되는 캐주얼 체험형 콘텐츠.</p>
          </div>
        </div>
      </div>
    </details>

  </div>
</section>

    <section id="skills" class="fade-in py-16 border-b border-gray-200 dark:border-gray-700">
  <h2 class="text-2xl font-semibold mb-6">✒️Skills</h2>
  <div class="space-y-6">
    <!-- 기술 항목 -->
    <div>
      <div class="flex items-center mb-1 text-base font-medium">
        <img src="https://img.icons8.com/?size=48&id=37619&format=png" alt="Microsoft Office" class="w-5 h-5 mr-2">
        Microsoft Office
      </div>
      <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2">
        <div class="bg-blue-500 h-2 rounded-full" style="width: 100%;"></div>
      </div>
    </div>
    <div>
      <div class="flex items-center mb-1 text-base font-medium">
        <img src="https://img.icons8.com/?size=48&id=17949&format=png" alt="Google Workspace" class="w-5 h-5 mr-2">
        Google Workspace
      </div>
      <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2">
        <div class="bg-purple-500 h-2 rounded-full" style="width: 100%;"></div>
      </div>
    </div>
    <div>
      <div class="flex items-center mb-1 text-base font-medium">
        <img src="https://i.namu.wiki/i/5FN7hLXcBd94b3Bi4MKCey6plbJSHZmjafZ-GL6cEcizRyauYLx6wK1VFtKuX0chDjCTMvX05EcaNetn0wpK-Q.svg" alt="Hancom HWP" class="w-5 h-5 mr-2">
        Hancom HWP
      </div>
      <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2">
        <div class="bg-pink-500 h-2 rounded-full" style="width: 100%;"></div>
      </div>
    </div>
    <div>
      <div class="flex items-center mb-1 text-base font-medium">
        <img src="https://img.icons8.com/?size=48&id=13677&format=png" alt="Adobe Photoshop" class="w-5 h-5 mr-2">
        Adobe Photoshop
      </div>
      <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2">
        <div class="bg-gray-900 dark:bg-gray-100 h-2 rounded-full" style="width: 70%;"></div>
      </div>
    </div>
    <div>
      <div class="flex items-center mb-1 text-base font-medium">
        <img src="https://img.icons8.com/?size=48&id=eoxMN35Z6JKg&format=png" alt="Gen-AI 활용" class="w-5 h-5 mr-2">
        Using Gen AI (e.g. Chatgpt, Gemini, Genspark, Flux Playground)
      </div>
      <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2">
        <div class="bg-green-500 h-2 rounded-full" style="width: 70%;"></div>
      </div>
    </div>
  </div>
</section>

<section id="gallery" class="fade-in py-16">
  <h2 class="text-2xl font-semibold mb-6">🖼️Work Gallery</h2>
  <div class="relative w-full max-w-4xl mx-auto px-4">
    <div class="swiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide relative">
          <img src="https://live.staticflickr.com/65535/54617007624_525995501c_h.jpg" alt="Image 1" class="rounded-lg w-full aspect-video object-cover">
          <div class="absolute inset-0 bg-gradient-to-r from-black/60 via-transparent to-black/60"></div>
        </div>
        <div class="swiper-slide relative">
          <img src="https://live.staticflickr.com/65535/54617014513_256f2d06d8_b.jpg" alt="Image 2" class="rounded-lg w-full aspect-video object-cover">
          <div class="absolute inset-0 bg-gradient-to-r from-black/60 via-transparent to-black/60"></div>
        </div>
        <div class="swiper-slide relative">
          <img src="https://live.staticflickr.com/65535/54616787871_9ca0d562b4_h.jpg" alt="Image 3" class="rounded-lg w-full aspect-video object-cover">
          <div class="absolute inset-0 bg-gradient-to-r from-black/60 via-transparent to-black/60"></div>
        </div>
        <div class="swiper-slide relative">
          <img src="https://live.staticflickr.com/65535/54615912952_6a2c0b1752_h.jpg" alt="Image 4" class="rounded-lg w-full aspect-video object-cover">
          <div class="absolute inset-0 bg-gradient-to-r from-black/60 via-transparent to-black/60"></div>
        </div>
        <div class="swiper-slide relative">
          <img src="https://live.staticflickr.com/65535/54617014518_f15c3b84de_h.jpg" alt="Image 5" class="rounded-lg w-full aspect-video object-cover">
          <div class="absolute inset-0 bg-gradient-to-r from-black/60 via-transparent to-black/60"></div>
        </div>
      </div>
      <div class="swiper-pagination"></div>
      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>
    </div>
  </div>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css"/>
  <script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
  <style>
    .swiper-pagination-bullet {
      background-color: #ccc;
      opacity: 1;
    }
    .dark .swiper-pagination-bullet {
      background-color: #999;
    }
    .swiper-pagination-bullet-active {
      background-color: #3b82f6;
    }
  </style>
  <script>
    new Swiper('.swiper', {
      loop: true,
      centeredSlides: true,
      slidesPerView: 1.05,
      spaceBetween: 10,
      pagination: {
        el: '.swiper-pagination',
        clickable: true,
      },
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
    });
  </script>
</section>
    
  <!-- Footer -->
<section id="contact" class="fade-in max-w-[900px] mx-auto px-6 py-16 space-y-1">
    <h2><strong>Contact</strong></h2>
    <p>Email: <a href="mailto:mdspc@naver.com">mdspc@naver.com</a></p>
    <p>Address: 206, Gwangmyeong-ro, Jungwon-gu, Seongnam-si, Gyeonggi-do, SOUTH KOREA</p><br>
    <div class="flex gap-4 items-center">
      <a href="https://www.facebook.com/nch0525" target="_blank" aria-label="Facebook">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook Icon" width="24" height="24">
      </a>
      <a href="https://x.com/chnoh_" target="_blank" aria-label="X (Twitter)">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" alt="X Icon" width="24" height="24">
      </a>
      <a href="https://bsky.app/profile/damonvr.bsky.social" target="_blank" aria-label="Bluesky">
        <img src="https://img.icons8.com/?size=48&id=3ovMFy5JDSWq&format=png" alt="Bluesky Icon" width="24" height="24">
      </a>
    </div>
  </section>

  <footer class="max-w-[900px] mx-auto px-6 py-8 text-center text-sm text-gray-400 dark:text-gray-500">
    <p>&copy; 2025 NOH CHOONG HYEON. Designed with vibe coding using Gen AI.</p>
  </footer>

  <button class="scroll-top" onclick="scrollToTop()">↑</button>

  <script>
    function toggleMode() {
      document.body.classList.toggle('light');
    }
    function scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
    function toggleDropdown(id) {
      const content = document.getElementById(id);
      if (!content) {
        console.warn(`Dropdown with id '${id}' not found.`);
        return;
      }
      content.classList.toggle('hidden');
    }
  </script>
<div id="popup" style="display:none; position:fixed; top:0; left:0; width:100vw; height:100vh; background:rgba(0,0,0,0.8); justify-content:center; align-items:center; z-index:10000;">
  <div id="popup-content" style="position:relative; max-width:80%; max-height:80%;">
    <button onclick="closePopup()" style="position:absolute; top:-2rem; right:0; padding:0.5rem 1rem; background:var(--accent); color:black; border:none; border-radius:4px; cursor:pointer;">Close</button>
    <div id="popup-media" style="display:flex; gap:1rem; overflow-x:auto;"></div>
  </div>
</div>
<script>
  function openPopup(items) {
    const popup = document.getElementById('popup');
    const container = document.getElementById('popup-media');
    container.innerHTML = '';
    items.forEach(src => {
      let el;
      if (src.includes('youtube.com')) {
        el = document.createElement('iframe');
        el.src = src;
        el.width = '560';
        el.height = '315';
        el.frameBorder = '0';
        el.allowFullscreen = true;
      } else {
        el = document.createElement('img');
        el.src = src;
        el.style = 'max-height: 400px; border-radius: 8px;';
      }
      container.appendChild(el);
    });
    popup.style.display = 'flex';
  }
  function closePopup() {
    document.getElementById('popup').style.display = 'none';
  }


  
</script>
</html>


