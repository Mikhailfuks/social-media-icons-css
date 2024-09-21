/* Basic styling for social media icons */
.social-icons {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 20px;
}

.social-icons a {
  display: inline-block;
  margin: 0 10px;
  padding: 10px;
  border-radius: 50%;
  background-color: #f2f2f2; /* Light gray background */
  color: #333;             /* Dark gray icon color */
  text-decoration: none;
  transition: background-color 0.3s ease; /* Smooth transition for hover effect */
}

.social-icons a:hover {
  background-color: #ddd; /* Slightly darker gray on hover */
}

/* Specific icons using Font Awesome */
.fa-facebook {
  font-size: 20px;
}

.fa-twitter {
  font-size: 20px;
}

.fa-instagram {
  font-size: 20px;
}

/* Example usage in HTML */
<div class="social-icons">
  <a href="#" target="_blank">
    <i class="fab fa-facebook"></i>
  </a>
  <a href="#" target="_blank">
    <i class="fab fa-twitter"></i>
  </a>
  <a href="#" target="_blank">
    <i class="fab fa-instagram"></i>
  </a>
</div>
