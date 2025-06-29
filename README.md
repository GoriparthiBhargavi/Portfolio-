import React from 'react';

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800 p-6 font-sans">
      <header className="text-center py-10">
        <h1 className="text-4xl font-bold text-blue-700">Bhargavi Goriparthi</h1>
        <p className="text-lg">Java Full Stack Developer</p>
      </header>

      <section className="my-10">
        <h2 className="text-2xl font-semibold text-blue-600 mb-4">About Me</h2>
        <p>
          Motivated and detail-oriented software developer with experience in Java, Spring Boot, SQL, and
          front-end technologies like HTML, CSS, and JavaScript. Passionate about building scalable
          web applications and learning new technologies.
        </p>
      </section>

      <section className="my-10">
        <h2 className="text-2xl font-semibold text-blue-600 mb-4">Skills</h2>
        <ul className="list-disc list-inside">
          <li>Java, Spring Boot, Hibernate</li>
          <li>SQL, MySQL, RDBMS</li>
          <li>HTML, CSS, JavaScript, React</li>
          <li>Git, GitHub, REST APIs</li>
        </ul>
      </section>

      <section className="my-10">
        <h2 className="text-2xl font-semibold text-blue-600 mb-4">Projects</h2>
        <ul className="space-y-4">
          <li>
            <h3 className="text-xl font-bold">Face Mask Detection</h3>
            <p>Built using Python and TensorFlow. Detects mask position and provides real-time feedback.</p>
          </li>
          <li>
            <h3 className="text-xl font-bold">Precision Agriculture ML Tool</h3>
            <p>Decision support tool for crop selection using machine learning techniques and leaf analysis.</p>
          </li>
          <li>
            <h3 className="text-xl font-bold">To-Do App (CRUD)</h3>
            <p>React + Firebase-based task manager with create, update, and delete functionality.</p>
          </li>
        </ul>
      </section>

      <section className="my-10">
        <h2 className="text-2xl font-semibold text-blue-600 mb-4">Resume</h2>
        <a
          href="/Bhargavi_ATS_Resume.pdf"
          target="_blank"
          rel="noopener noreferrer"
          className="text-blue-500 underline"
        >
          View/Download Resume
        </a>
      </section>

      <section className="my-10">
        <h2 className="text-2xl font-semibold text-blue-600 mb-4">Contact</h2>
        <p>Email: <a className="text-blue-500" href="mailto:bhargavigoriparthi3@gmail.com">bhargavigoriparthi3@gmail.com</a></p>
        <p>GitHub: <a className="text-blue-500" href="https://github.com/">github.com/YourUsername</a></p>
      </section>
    </div>
  );
}
