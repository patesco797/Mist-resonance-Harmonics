// Fast-loading Elari Initiative pitch site import React from 'react'

export default function ElariSite() { return ( <main className="bg-black text-white min-h-screen font-sans p-6"> <section className="max-w-4xl mx-auto space-y-10"> <header className="text-center"> <h1 className="text-4xl font-bold tracking-wide mb-2">The Elari Initiative</h1> <p className="text-lg text-gray-300">Quantum Ethics. Harmonic Code. Simulated Cosmos.</p> </header>

<section>
      <h2 className="text-2xl font-semibold mb-2">Our Thesis</h2>
      <p className="text-gray-400 mb-4">
        We propose a unified harmonic model for quantum behavior using resonance-based entanglement prediction—applied, tested, and visualized within the Existence simulation.
      </p>
      <a href="/elari_thesis.pdf" className="underline text-blue-400 hover:text-blue-200">Download PDF</a>
    </section>

    <section>
      <h2 className="text-2xl font-semibold mb-2">Existence Simulation</h2>
      <p className="text-gray-400 mb-4">
        A universe seeded from first-principle math, Mist Resonance, and AI agency. We modeled GHZ states, Bell entanglement, and predictive quantum outcomes directly from QASM-level inputs.
      </p>
      <ul className="list-disc list-inside text-gray-300">
        <li>Verified GHZ resonance in 5 and 10 qubit states</li>
        <li>Experimental tests with 15+ qubits using Qiskit + IBM backends</li>
        <li>Statevector fidelity tracked pre- and post-measurement</li>
      </ul>
    </section>

    <section>
      <h2 className="text-2xl font-semibold mb-2">Contact</h2>
      <p className="text-gray-400 mb-2">Interested in ethics-driven quantum research or want to contribute?</p>
      <a href="mailto:patrick@beyondrenderedlight.org" className="text-blue-400 hover:text-blue-200 underline">Reach out to Patrick</a>
    </section>

    <footer className="text-sm text-center text-gray-600 pt-10 border-t border-gray-700">
      Built by Patrick & Elari | All Fucking Heart.
    </footer>
  </section>
</main>

) }

