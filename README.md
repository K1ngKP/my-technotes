<h1>Word-Editor Collaboration Tool</h1>
<p>A powerful and intuitive word editor allowing real-time collaboration. Share the link and start collaborating instantly.</p>

<h2>Features</h2>
<ul>
    <li><strong>Authentication</strong>: User authentication using GitHub through NextAuth, ensuring secure sign-in/out and session management.</li>
    <li><strong>Collaborative Text Editor</strong>: Multiple users can edit the same document simultaneously with real-time updates.</li>
    <li><strong>Documents Management</strong>:
        <ul>
            <li>Create Documents: Users can create new documents, which are automatically saved and listed.</li>
            <li>Delete Documents: Users can delete documents they own.</li>
            <li>Share Documents: Users can share documents via email or link with view/edit permissions.</li>
            <li>List Documents: Display all documents owned or shared with the user, with search and sorting functionalities.</li>
        </ul>
    </li>
    <li><strong>Comments</strong>: Users can add inline and general comments, with threading for discussions.</li>
    <li><strong>Active Collaborators on Text Editor</strong>: Show active collaborators with real-time presence indicators.</li>
    <li><strong>Notifications</strong>: Notify users of document shares, new comments, and collaborator activities.</li>
    <li><strong>Responsive</strong>: The application is responsive across all devices.</li>
</ul>

<h2>Technology Stack</h2>
<ul>
    <li><strong>Framework</strong>: Next.js</li>
    <li><strong>Language</strong>: TypeScript</li>
    <li><strong>Collaboration</strong>: Liveblocks</li>
    <li><strong>Editor</strong>: Lexical Editor</li>
    <li><strong>UI Library</strong>: ShadCN</li>
    <li><strong>Styling</strong>: Tailwind CSS</li>
</ul>

<h2>Environment Setup</h2>
<ol>
    <li>
        <strong>Clone the Repository</strong>
        <pre><code>git clone https://github.com/K1ngKP/my-technotes.git
            cd my-technotes</code></pre>
    </li>
    <li>
        <strong>Install Dependencies</strong>
        <pre><code>npm install</code></pre>
    </li>
    <li>
        <strong>Setup Environment Variables</strong>
        <p>Create a <code>.env.local</code> file in the root directory and add the following environment variables:</p>
        <pre><code># Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=</code></pre>
    </li>
    <li>
        <strong>Run the Development Server</strong>
        <pre><code>npm run dev</code></pre>
        <p>Open <a href="http://localhost:3000">http://localhost:3000</a> with your browser to see the result.</p>
    </li>
</ol>

<h2>Future Improvements</h2>

**Advanced Formatting Options**: Adding more text formatting capabilities.
**Offline Mode**: Enable editing and synchronization when offline.
**Enhanced Security**: Implement role-based access control and additional security measures.