export default function Portfolio() {
  const projects = [
    { title: "Customer Segmentation Analysis", status: "Coming Soon" },
    { title: "Sales Trend Prediction with Python", status: "Coming Soon" },
    { title: "SQL Data Cleaning Project", status: "Coming Soon" }
  ];

  return (
    <div className="min-h-screen bg-gray-100 p-6">
      <div className="max-w-3xl mx-auto bg-white p-6 rounded-2xl shadow-lg">
        {/* About Me Section */}
        <section className="mb-6">
          <h1 className="text-3xl font-bold text-gray-800">About Me</h1>
          <p className="text-gray-600 mt-2">
            Hi, I'm a data enthusiast currently transitioning into Data Analytics. I love working with data
            to extract insights and build solutions that drive decision-making.
          </p>
        </section>

        {/* Upcoming Projects Section */}
        <section className="mb-6">
          <h2 className="text-2xl font-bold text-gray-800">Upcoming Projects</h2>
          <ul className="mt-2 space-y-2">
            {projects.map((project, index) => (
              <li key={index} className="p-3 bg-gray-200 rounded-lg">
                <span className="font-semibold">{project.title}</span> - {project.status}
              </li>
            ))}
          </ul>
        </section>

        {/* Contact Me Section */}
        <section>
          <h2 className="text-2xl font-bold text-gray-800">Contact Me</h2>
          <p className="text-gray-600 mt-2">Feel free to reach out for collaborations or discussions.</p>
          <a
            href="mailto:your.email@example.com"
            className="mt-3 inline-block bg-blue-500 text-white px-4 py-2 rounded-xl shadow-md hover:bg-blue-600"
          >
            Email Me
          </a>
        </section>
      </div>
    </div>
  );
}
