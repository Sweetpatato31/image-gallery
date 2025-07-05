<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Travel Log Lissabon</title>

  <style>
    @charset "UTF-8";

    *,
    *:before,
    *:after {
      box-sizing: border-box;
    }

    html {
      font-size: 16px;
    }

    body {
      font-family: helvetica;
      position: relative;
      font-size: 100%;
      background: linear-gradient(to right, #333333, #0e0e0e);
    }

    .cover-container {
      position: relative;
      width: 100%;
      height: 100vh;
      overflow: hidden;
    }

    .cover-container img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      cursor: pointer;
      transition: opacity 1s ease;
    }

    .gallery {
      opacity: 0;
      visibility: hidden;
      transition: opacity 1s ease, visibility 1s ease;
      padding: 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1rem;
    }

    .gallery.show {
      opacity: 1;
      visibility: visible;
    }

    .gallery img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
    }
    
    .gallery-container {
      padding: 0.9375rem 0;
    }

    .gallery-container h1 {
      margin: 2rem 0;
      padding: 0;
      text-align: center;
      color: #fff;
      text-transform: uppercase;
      font-size: 6.5vw;
      font-weight: lighter;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-gap: 8px;
      max-width: 1200px;
      width: 100%;
      margin: 0 auto;
    }

    @media (min-width: 20em) {
      .gallery-grid {
        grid-template-columns: repeat(1, 1fr);
      }
    }

    @media (min-width: 34em) {
      .gallery-grid {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media (min-width: 60em) {
      .gallery-grid {
        grid-template-columns: repeat(3, 1fr);
      }
    }

    .gallery-grid img {
      width: 100%;
      border: 5px solid #fff;
    }

    .gallery-grid div {
      position: relative;
      cursor: pointer;
    }

    .gallery-grid div:before,
    .gallery-grid div:after {
      transition: 0.3s opacity ease;
      opacity: 0;
    }

    .gallery-grid div:after {
      content: "↔";
      font-size: 80px;
      position: absolute;
      transform: translate3d(-50%, -50%, 0) rotate(-45deg);
      color: #fff;
      left: 50%;
      top: 50%;
      display: block;
    }

    .gallery-grid div:before {
      content: "";
      position: absolute;
      top: 0;
      bottom: 4px;
      left: 0;
      right: 0;
      background: rgba(34, 34, 34, 0.5);
      display: block;
    }

    .gallery-grid div:hover:before,
    .gallery-grid div:hover:after {
      opacity: 1;
      transition: 0.3s opacity ease;
    }

    .modal {
      position: fixed;
      z-index: 999;
      width: 50%;
      max-width: 800px;
      top: 50%;
      left: 50%;
      transform: translate3d(-50%, -50%, 0);
    }

    @media (min-width: 20em) {
      .modal {
        width: 95%;
      }
    }

    @media (min-width: 34em) {
      .modal {
        width: 80%;
      }
    }

    @media (min-width: 60em) {
      .modal {
        width: 60%;
      }
    }

    .modal img {
      width: 100%;
      border: 5px solid #fff;
    }

    .modal-overlay {
      position: fixed;
      z-index: 1;
      height: 100%;
      width: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      top: 0;
      left: 0;
    }

    .modal-body a {
      position: absolute;
      display: inline;
      color: #222;
      text-decoration: none;
      line-height: 36px;
      font-size: 30px;
      font-weight: lighter;
      background: #fff;
      border-radius: 5px;
      height: 40px;
      width: 40px;
      text-align: center;
    }

    .modal-body .modal-close {
      right: 0;
      top: 0;
      border-radius: 0 0 0 5px;
    }

    .modal-body .modal-next,
    .modal-body .modal-prev {
      right: 0;
      top: calc(50% - 25px);
      border-radius: 5px 0 0 5px;
      height: 50px;
      line-height: 40px;
      font-size: 60px;
    }

    .modal-body .modal-prev {
      left: 0;
      right: auto;
      border-radius: 0 5px 5px 0;
    }

    .modal-body {
      position: relative;
    }
    .gallery:not(.show) .gallery-grid,
    .gallery:not(.show) h1 {
      opacity: 0;
      visibility: hidden;
      transition: opacity 1s ease, visibility 1s ease;
    }
    
    .gallery.show .gallery-grid,
    .gallery.show h1 {
      opacity: 1;
      visibility: visible;
    }
  </style>

</head>

<body>
 <!-- Cover Section -->
  <div class="cover-container" id="coverContainer">
    <img id="coverImage" src="cover.png" alt="Cover" onclick="fadeToGallery()">
  </div>
  
  <!-- partial:index.partial.html -->
  <section class="gallery-container gallery" id="gallery"></section>
  <!-- partial -->
  <script src='https://cdnjs.cloudflare.com/ajax/libs/react/15.4.2/react.min.js'></script>
  <script src='https://cdnjs.cloudflare.com/ajax/libs/react/15.4.2/react-dom.min.js'></script>

  <script>
      const imgUrls = ['1.png', '2.png', '3.png', '4.png', '5.png', '6.png', '7.png', '8.png', '9.png', '10.png', '11.png', '12.png', '13.png', '14.png', '15.png', '16.png', '17.png', '18.png', '19.png', '20.png', '21.png', '22.png', '23.png', '24.png', '25.png', '26.png', '27.png', '28.png', '29.png', '30.png', '31.png', '32.png', '33.png', '34.png', '35.png', '36.png', '37.png', '38.png', '39.png', '40.png', '41.png', '42.png', '43.png', '44.png', '45.png', '46.png', '47.png', '48.png', '49.png', '50.png', '51.png', '52.png', '53.png', '54.png', '55.png', '56.png', '57.png', '58.png', '59.png', '60.png', '61.png', '62.png', '63.png', '64.png', '65.png', '66.png', '67.png', '68.png', '69.png', '70.png', '71.png', '72.png', '73.png', '74.png', '75.png', '76.png', '77.png', '78.png', '79.png', '80.png', '81.png', '82.png', '83.png', '84.png', '85.png', '86.png', '87.png', '88.png', '89.png', '90.png', '91.png', '92.png', '93.png', '94.png', '95.png', '96.png', '97.png', '98.png', '99.png', '100.png', '101.png', '102.png', '103.png', '104.png', '105.png', '106.png', '107.png', '108.png', '109.png', '110.png', '111.png'];

    function fadeToGallery() {
      const coverImage = document.getElementById("coverImage");
      const gallery = document.getElementById("gallery");

      coverImage.style.opacity = "0";

      setTimeout(() => {
        document.getElementById("coverContainer").style.display = "none";
        gallery.classList.add("show");
      }, 600);
    }

      class Gallery extends React.Component {
      constructor(props) {
        super(props);
        this.state = { currentIndex: null };
        this.closeModal = this.closeModal.bind(this);
        this.findNext = this.findNext.bind(this);
        this.findPrev = this.findPrev.bind(this);
        this.renderImageContent = this.renderImageContent.bind(this);
      }
      renderImageContent(src, index) {
        return /*#__PURE__*/(
          React.createElement("div", { onClick: e => this.openModal(e, index) }, /*#__PURE__*/
            React.createElement("img", { src: src, key: src })));


      }
      openModal(e, index) {
        this.setState({ currentIndex: index });
      }
      closeModal(e) {
        if (e != undefined) {
          e.preventDefault();
        }
        this.setState({ currentIndex: null });
      }
      findPrev(e) {
        if (e != undefined) {
          e.preventDefault();
        }
        this.setState(prevState => ({
          currentIndex: prevState.currentIndex - 1
        }));

      }
      findNext(e) {
        if (e != undefined) {
          e.preventDefault();
        }
        this.setState(prevState => ({
          currentIndex: prevState.currentIndex + 1
        }));

      }
      render() {
        return /*#__PURE__*/(
          React.createElement("div", { className: "gallery-container" }, /*#__PURE__*/
            React.createElement("h1", null, "Lissabon"), /*#__PURE__*/
            React.createElement("div", { className: "gallery-grid" },
              imgUrls.map(this.renderImageContent)), /*#__PURE__*/

            React.createElement(GalleryModal, {
              closeModal: this.closeModal,
              findPrev: this.findPrev,
              findNext: this.findNext,
              hasPrev: this.state.currentIndex > 0,
              hasNext: this.state.currentIndex + 1 < imgUrls.length,
              src: imgUrls[this.state.currentIndex]
            })));



      }
    }


    class GalleryModal extends React.Component {
      constructor() {
        super();
        this.handleKeyDown = this.handleKeyDown.bind(this);
      }
      componentDidMount() {
        document.body.addEventListener('keydown', this.handleKeyDown);
      }
      componentWillUnMount() {
        document.body.removeEventListener('keydown', this.handleKeyDown);
      }
      handleKeyDown(e) {
        if (e.keyCode === 27)
          this.props.closeModal();
        if (e.keyCode === 37 && this.props.hasPrev)
          this.props.findPrev();
        if (e.keyCode === 39 && this.props.hasNext)
          this.props.findNext();
      }
      render() {
        const { closeModal, hasNext, hasPrev, findNext, findPrev, src } = this.props;
        if (!src) {
          console.log('whut');
          return null;
        }
        return /*#__PURE__*/(
          React.createElement("div", null, /*#__PURE__*/
            React.createElement("div", { className: "modal-overlay", onClick: closeModal }), /*#__PURE__*/
            React.createElement("div", { isOpen: !!src, className: "modal" }, /*#__PURE__*/
              React.createElement("div", { className: "modal-body" }, /*#__PURE__*/
                React.createElement("a", { href: "#", className: "modal-close", onClick: closeModal, onKeyDown: this.handleKeyDown }, "\xD7"),
                hasPrev && /*#__PURE__*/React.createElement("a", { href: "#", className: "modal-prev", onClick: findPrev, onKeyDown: this.handleKeyDown }, "\u2039"),
                hasNext && /*#__PURE__*/React.createElement("a", { href: "#", className: "modal-next", onClick: findNext, onKeyDown: this.handleKeyDown }, "\u203A"), /*#__PURE__*/
                React.createElement("img", { src: src })))));




      }
    }


    ReactDOM.render( /*#__PURE__*/React.createElement(Gallery, null), document.querySelector('.gallery-container'));
  </script>

</body>

</html>
