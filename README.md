<script>
  document.addEventListener('DOMContentLoaded', function () {
    var widget = document.createElement('div');
    widget.id = 'feedback-widget';
    widget.style.position = 'fixed';
    widget.style.bottom = '20px';
    widget.style.right = '20px';
    widget.style.background = '#007BFF';
    widget.style.color = '#fff';
    widget.style.padding = '10px 20px';
    widget.style.borderRadius = '5px';
    widget.style.cursor = 'pointer';
    widget.innerText = 'Feedback';
    
    widget.onclick = function () {
      alert('Feedback clicked!');
    };
    
    document.body.appendChild(widget);
  });
</script>


# gitbook

Something new
