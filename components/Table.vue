<template>
  <table class="table">
    <!-- Caption -->
    <caption>
      We can make tables too.
    </caption>
    <!-- Colgroup and Col -->
    <colgroup>
      <col span="1" />
      <col span="1" />
      <col span="1" />
      <col span="1" />
    </colgroup>
    <!-- Table Head -->
    <thead>
      <tr>
        <th>Element</th>
        <th>Purpose</th>
        <th>Used?</th>
        <th>Notes</th>
      </tr>
    </thead>
    <!-- Table Body -->
    <tbody>
      <tr>
        <td>&lt;html&gt;</td>
        <td>The root element of the page</td>
        <td>✔️</td>
        <td>Without this, you're not doing HTML.</td>
      </tr>
      <tr>
        <td>&lt;marquee&gt; (deprecated)</td>
        <td>Scrolling text</td>
        <td>X</td>
        <td>Now that would've been fun.</td>
      </tr>
      <tr>
        <td>&lt;blink&gt; (deprecated)</td>
        <td>Flashing text</td>
        <td>X️</td>
        <td>This one not so much.</td>
      </tr>
    </tbody>
    <!-- Table Footer -->
    <tfoot>
      <tr>
        <td colspan="4">
          Disclaimer: No web standards were harmed in the making of this table.
        </td>
      </tr>
    </tfoot>
  </table>
</template>
