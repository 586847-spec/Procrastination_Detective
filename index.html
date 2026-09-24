<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Procrastination Detective</title>

    <style>
      :root {
        color-scheme: light;
        font-family: Inter, ui-sans-serif, system-ui, -apple-system,
          BlinkMacSystemFont, "Segoe UI", sans-serif;
        color: #2f2419;
        background: #f4ead7;
      }

      * {
        box-sizing: border-box;
      }

      body {
        min-height: 100vh;
        margin: 0;
        padding: 24px;
        background:
          radial-gradient(
            circle at top left,
            rgba(255, 255, 255, 0.6),
            transparent 35%
          ),
          #f4ead7;
      }

      .case-file {
        width: min(100%, 760px);
        margin: 0 auto;
        padding: clamp(28px, 6vw, 64px);
        border: 2px solid #d6bd93;
        border-radius: 12px;
        background: #fffaf0;
        box-shadow: 8px 10px 0 rgba(105, 74, 40, 0.12);
      }

      .stamp {
        display: inline-block;
        margin-bottom: 18px;
        padding: 7px 12px;
        border: 2px solid #bc543e;
        color: #bc543e;
        font-size: 0.78rem;
        font-weight: 800;
        letter-spacing: 0.12em;
        text-transform: uppercase;
        transform: rotate(-2deg);
      }

      h1,
      h2 {
        margin: 0;
        color: #3e2d20;
        font-family: Georgia, "Times New Roman", serif;
      }

      h1 {
        max-width: 620px;
        font-size: clamp(2.5rem, 8vw, 5.2rem);
        line-height: 0.98;
      }

      h2 {
        font-size: clamp(2rem, 5vw, 3.2rem);
      }

      .subtitle,
      .intro {
        max-width: 560px;
        margin: 20px 0 0;
        color: #715d4a;
        font-size: 1.1rem;
        line-height: 1.7;
      }

      .clue {
        margin: 30px 0 0;
        padding: 14px 18px;
        border-left: 4px solid #d69d3e;
        background: #fff2c9;
        color: #624822;
        font-weight: 700;
      }

      .question {
        margin: 28px 0 0;
      }

      label {
        display: block;
        margin-bottom: 9px;
        color: #604b38;
        font-weight: 800;
      }

      select {
        width: 100%;
        padding: 13px 14px;
        border: 1px solid #cdb795;
        border-radius: 8px;
        color: #34271c;
        background: #fffdf8;
        font: inherit;
      }

      select:focus,
      button:focus-visible {
        outline: 3px solid #e7b95e;
        outline-offset: 3px;
      }

      .actions {
        display: flex;
        flex-wrap: wrap;
        gap: 12px;
        margin-top: 34px;
      }

      button {
        padding: 13px 20px;
        border: 0;
        border-radius: 8px;
        color: #fffaf0;
        background: #3e2d20;
        cursor: pointer;
        font: inherit;
        font-weight: 800;
        transition: transform 160ms ease, background 160ms ease;
      }

      button:hover {
        background: #5b3f2a;
        transform: translateY(-1px);
      }

      button.secondary {
        color: #604b38;
        border: 1px solid #cdb795;
        background: transparent;
      }

      button.secondary:hover {
        background: #f7ecd8;
      }

      .result {
        margin-top: 28px;
        padding: 24px;
        border: 1px dashed #bc543e;
        background: #fff3dc;
      }

      .result h3 {
        margin: 0;
        color: #bc543e;
        font-family: Georgia, "Times New Roman", serif;
        font-size: 1.8rem;
      }

      .route-label {
        margin: 8px 0 0;
        color: #bc543e;
        font-size: 0.78rem;
        font-weight: 800;
        letter-spacing: 0.08em;
        line-height: 1.5;
        text-transform: uppercase;
      }

      .result p {
        margin: 12px 0 0;
        color: #604b38;
        line-height: 1.65;
      }

      .evidence {
        margin-top: 20px;
        padding: 14px 16px;
        border-left: 4px solid #d69d3e;
        background: #fff2c9;
        color: #624822;
        line-height: 1.6;
      }

      .mission {
        margin-top: 20px;
        padding: 18px 20px;
        border: 1px solid #d6bd93;
        border-radius: 8px;
        background: #fffaf0;
      }

      .mission h4 {
        margin: 0;
        color: #3e2d20;
        font-family: Georgia, "Times New Roman", serif;
        font-size: 1.25rem;
      }

      .mission ol {
        margin: 12px 0 0;
        padding-left: 22px;
        color: #604b38;
        line-height: 1.7;
      }

      .hidden {
        display: none;
      }

      @media (max-width: 540px) {
        body {
          padding: 12px;
        }

        .case-file {
          padding: 28px 20px;
        }
      }
    </style>
  </head>

  <body>
    <main class="case-file">
      <section id="screen1" aria-labelledby="welcome-title">
        <span class="stamp">Case file: open</span>

        <h1 id="welcome-title">
          🕵️‍♂️ Procrastination Detective
        </h1>

        <p class="subtitle">
          Cracking the case on your roadblocks.
        </p>

        <p class="clue">
          No judgment. Just clues, patterns, and one tiny next step.
        </p>

        <div class="actions">
          <button type="button" onclick="goToQuestions()">
            I don't wanna start
          </button>
        </div>
      </section>

      <section
        id="screen2"
        class="hidden"
        aria-labelledby="investigation-title"
      >
        <span class="stamp">Investigation in progress</span>

        <h2 id="investigation-title">
          The Investigation
        </h2>

        <p class="intro">
          Answer honestly. The detective is on your side.
        </p>

        <div class="question">
          <label for="q1">
            1) What are you working on?
          </label>

          <select id="q1">
            <option value="test">Studying for a test</option>
            <option value="essay">An essay</option>
            <option value="homework">Homework</option>
            <option value="project">A computer project</option>
            <option value="reading">Reading or taking notes</option>
            <option value="presentation">A presentation</option>
            <option value="creative">A creative project</option>
            <option value="life-admin">A chore or life task</option>
          </select>
        </div>

        <div class="question">
          <label for="q2">
            2) How long will this probably take?
          </label>

          <select id="q2">
            <option value="10min">10 minutes or less</option>
            <option value="15min">15 minutes</option>
            <option value="30min">30 minutes</option>
            <option value="hour">About an hour</option>
            <option value="hours">A few hours</option>
            <option value="days">A few days</option>
          </select>
        </div>

        <div class="question">
          <label for="q3">
            3) Why don't you even start?
          </label>

          <select id="q3">
            <option value="overwhelmed">
              It feels like too much
            </option>
            <option value="confused">
              I don't understand it
            </option>
            <option value="lost">
              I don't know where to start
            </option>
            <option value="anxious">
              I'm worried that I'll mess it up
            </option>
            <option value="bored">
              I'd rather do something else
            </option>
          </select>
        </div>

        <div class="question">
          <label for="q4">
            4) Are you tired?
          </label>

          <select id="q4">
            <option value="no">No</option>
            <option value="little">A little</option>
            <option value="yes">Yes</option>
            <option value="exhausted">Very tired</option>
          </select>
        </div>

        <div class="question">
          <label for="q5">
            5) Is the assignment hard or are you confused?
          </label>

          <select id="q5">
            <option value="hard">It's hard</option>
            <option value="both">It's hard and confusing</option>
            <option value="confused">I'm confused</option>
            <option value="neither">Neither</option>
          </select>
        </div>

        <div class="question">
          <label for="q6">
            6) Have you started yet?
          </label>

          <select id="q6">
            <option value="no">No</option>
            <option value="barely">Barely</option>
            <option value="halfway">I'm about halfway done</option>
            <option value="yes">Yes, but I'm stuck</option>
          </select>
        </div>

        <div class="actions">
          <button type="button" onclick="solveCase()">
            Solve the case
          </button>

          <button
            type="button"
            class="secondary"
            onclick="goHome()"
          >
            Start over
          </button>
        </div>
      </section>

      <section
        id="screen3"
        class="hidden"
        aria-labelledby="result-title"
      >
        <span class="stamp">Case solved</span>

        <h2 id="result-title">
          The Case File
        </h2>

        <div class="result" aria-live="polite">
          <h3 id="result-heading"></h3>
          <p id="route-label" class="route-label"></p>
          <p id="result-text"></p>

          <div class="evidence">
            <strong>Evidence found:</strong>
            <span id="result-evidence"></span>
          </div>

          <div class="mission">
            <h4>Your tiny mission</h4>
            <ol id="mission-steps"></ol>
          </div>
        </div>

        <div class="actions">
          <button type="button" onclick="startMission()">
            Start the tiny mission
          </button>

          <button
            type="button"
            class="secondary"
            onclick="goToQuestions()"
          >
            Investigate again
          </button>
        </div>
      </section>
    </main>

    <script>
      const labels = {
        task: {
          test: "studying for a test",
          essay: "writing an essay",
          homework: "doing homework",
          project: "building a computer project",
          reading: "reading or taking notes",
          presentation: "making a presentation",
          creative: "working on a creative project",
          "life-admin": "handling a chore or life task"
        },

        time: {
          "10min": "10 minutes or less",
          "15min": "about 15 minutes",
          "30min": "about 30 minutes",
          hour: "about an hour",
          hours: "a few hours",
          days: "a few days"
        },

        energy: {
          no: "your energy is okay",
          little: "you are a little tired",
          yes: "you are tired",
          exhausted: "your battery is very low"
        },

        progress: {
          no: "you have not started",
          barely: "you have barely started",
          halfway: "you are about halfway done",
          yes: "you have started but feel stuck"
        }
      };

      const baseRoutes = {
        overwhelmed: {
          text:
            "The task feels too large to hold in your head at once. " +
            "Your route is to shrink the first move until it feels harmless.",

          steps: [
            "Write down three checkpoints instead of the whole task.",
            "Choose the checkpoint that can be started in ten minutes.",
            "Work only until that checkpoint has a rough first version."
          ]
        },

        confused: {
          text:
            "The instructions are taking up more energy than the work itself. " +
            "Your route is to find one clear answer before pushing forward.",

          steps: [
            "Circle or copy the exact part that does not make sense.",
            "Turn it into one specific question.",
            "Check the instructions, an example, a classmate, or a teacher for that answer."
          ]
        },

        lost: {
          text:
            "You are not refusing to work—you are missing a clear starting line. " +
            "Your route is to make the first move impossible to debate.",

          steps: [
            "Open the assignment, document, or project.",
            "Write a rough title, checklist, or file name.",
            "Choose the smallest item and work on it for five minutes."
          ]
        },

        anxious: {
          text:
            "Fear of doing it wrong is blocking your progress. " +
            "Your route is to make a private, imperfect version that can be improved later.",

          steps: [
            "Make a rough version with no pressure to submit it.",
            "Mark the one part you understand best.",
            "Improve only that part before returning to the harder section."
          ]
        },

        bored: {
          text:
            "The reward is too far away, so your brain keeps looking for something easier. " +
            "Your route is to add a short timer and a visible finish line.",

          steps: [
            "Set a 10-minute timer and put your biggest distraction away.",
            "Work toward one small checkpoint, not the entire task.",
            "Take a short break when the timer ends, then choose whether to repeat."
          ]
        }
      };

      const taskRoutes = {
        test: "Study Sprint",
        essay: "Draft Mode",
        homework: "Assignment Mode",
        project: "Build Mode",
        reading: "Reading Mode",
        presentation: "Presentation Mode",
        creative: "Create Mode",
        "life-admin": "Life Admin Mode"
      };

      const timeRoutes = {
        "10min": "Quick Win",
        "15min": "Quick Win",
        "30min": "30-Minute Block",
        hour: "Deep Work",
        hours: "Long Haul",
        days: "Long Haul"
      };

      const energyRoutes = {
        no: "Full Energy",
        little: "Low Energy",
        yes: "Low Battery",
        exhausted: "Emergency Battery"
      };

      const difficultyRoutes = {
        hard: "Skill Wall",
        both: "Complex Task",
        confused: "Clarity Needed",
        neither: "Ready to Go"
      };

      const progressRoutes = {
        no: "Fresh Start",
        barely: "Warm-Up",
        halfway: "Momentum",
        yes: "Stuck Midway"
      };

      const routeTitles = {
        overwhelmed: {
          short: "The Tiny Overwhelm Route",
          medium: "The Break-It-Down Route",
          long: "The Giant Task Route"
        },

        confused: {
          short: "The Quick Clarification Route",
          medium: "The Fog-Clearing Route",
          long: "The Research Map Route"
        },

        lost: {
          short: "The First Click Route",
          medium: "The Starting Line Route",
          long: "The Project Map Route"
        },

        anxious: {
          short: "The Low-Stakes Draft Route",
          medium: "The Imperfect Start Route",
          long: "The High-Stakes Route"
        },

        bored: {
          short: "The Fast Reward Route",
          medium: "The Timer Route",
          long: "The Long-Haul Distraction Route"
        }
      };

      const taskSteps = {
        test: "Write three practice questions or review one small topic.",
        essay: "Open the document and write a rough title or first sentence.",
        homework: "Put the exact problem in front of you and underline the task.",
        project: "Open the project and create or name the next file you need.",
        reading: "Read one page or highlight three important ideas.",
        presentation: "Write the presentation title and three possible points.",
        creative: "Make one rough version without trying to make it perfect.",
        "life-admin":
          "Put the needed item, form, or materials directly in front of you."
      };

      function getTimeCategory(time) {
        if (time === "10min" || time === "15min") {
          return "short";
        }

        if (time === "30min" || time === "hour") {
          return "medium";
        }

        return "long";
      }

      function analyzeCase(answers) {
        const base = baseRoutes[answers.q3];
        const task = labels.task[answers.q1];
        const time = labels.time[answers.q2];
        const energy = labels.energy[answers.q4];
        const progress = labels.progress[answers.q6];
        const timeCategory = getTimeCategory(answers.q2);

        const routeSignals = [
          taskRoutes[answers.q1],
          timeRoutes[answers.q2],
          energyRoutes[answers.q4],
          difficultyRoutes[answers.q5],
          progressRoutes[answers.q6]
        ];

        const evidence =
          `You are ${task}, it will take ${time}, ` +
          `${energy}, and ${progress}.`;

        return {
          title:
            `${routeTitles[answers.q3][timeCategory]} — ` +
            `${taskRoutes[answers.q1]}`,

          text: base.text,

          steps: [
            taskSteps[answers.q1],
            ...base.steps.slice(1)
          ],

          evidence,
          routeLabel: routeSignals.join(" • ")
        };
      }

      function goToQuestions() {
        document
          .getElementById("screen1")
          .classList.add("hidden");

        document
          .getElementById("screen3")
          .classList.add("hidden");

        document
          .getElementById("screen2")
          .classList.remove("hidden");

        window.scrollTo({
          top: 0,
          behavior: "smooth"
        });
      }

      function goHome() {
        document
          .getElementById("screen2")
          .classList.add("hidden");

        document
          .getElementById("screen3")
          .classList.add("hidden");

        document
          .getElementById("screen1")
          .classList.remove("hidden");

        window.scrollTo({
          top: 0,
          behavior: "smooth"
        });
      }

      function solveCase() {
        const answers = {
          q1: document.getElementById("q1").value,
          q2: document.getElementById("q2").value,
          q3: document.getElementById("q3").value,
          q4: document.getElementById("q4").value,
          q5: document.getElementById("q5").value,
          q6: document.getElementById("q6").value
        };

        const selectedCase = analyzeCase(answers);

        document.getElementById("result-heading").textContent =
          selectedCase.title;

        document.getElementById("route-label").textContent =
          `Route: ${selectedCase.routeLabel}`;

        document.getElementById("result-text").textContent =
          selectedCase.text;

        document.getElementById("result-evidence").textContent =
          ` ${selectedCase.evidence}`;

        const missionSteps =
          document.getElementById("mission-steps");

        missionSteps.innerHTML = "";

        selectedCase.steps.forEach((step) => {
          const item = document.createElement("li");
          item.textContent = step;
          missionSteps.appendChild(item);
        });

        document
          .getElementById("screen2")
          .classList.add("hidden");

        document
          .getElementById("screen3")
          .classList.remove("hidden");

        window.scrollTo({
          top: 0,
          behavior: "smooth"
        });
      }

      function startMission() {
        document.getElementById("result-text").textContent =
          "Mission started. Follow step one now. " +
          "You only need enough momentum to crack the case.";
      }
    </script>
  </body>
</html>
