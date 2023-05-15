<script>
  let github_repo = "https://github.com/Abdulmumin1";
  const visit_github = () => {
    window.location.href = github_repo;
  };
</script>

<button on:click={visit_github}> Visit Github </button>
