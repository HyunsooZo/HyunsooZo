# HyunsooZo
<style>
.flex-box_wrap {
    display: flex;
    
    .img_char {
        flex: 0 1 auto;
        display: inline-flex;
        padding: 0 1rem;
        border: solid var(--border-secondary);
        border-width: 1px 0;
        line-height: 0;
        span {
            display: inline-block;
            max-width: 180px;
            margin: auto;
            padding:0 1rem 0 0;
        }
    }

    ._type__01 {
        width: 100%;
        border-top: 1px solid var(--border-secondary);
        
        li {
            display: flex;
            border-bottom: 1px solid var(--border-secondary);
            
            &:nth-child(even) {
                background: var(--background-secondary);
            }
            strong {
                display: inline-block;
                width: 40%;
                padding: 0.8rem;
                word-break: break-word;
            }
            .list_text {
                flex: 0 1 100%;
                padding: 0.8rem;
            }
        }
    }
    
    @media (max-width: $mobile-break) {
        flex-direction: column;
        
        .img_char {
            border: 0;
            span {
                max-width: 150px;
            }
        }
        ._type__01 li {
            flex-direction: column;
            padding: 0.8rem 0;
            
            strong {
                width: 100%;
                padding-bottom: 0;
                font-size: 1.5rem;
            }
        }
    }
}

.list_text {

    p {
        display: flex;
        align-items: flex-start;
        
        i {
            display: flex;
            align-items: center;
            height: 1.8rem;
            margin: 0.1rem 0.6rem 0 0;

            img {
                height: 1.5rem;
            }
        }
        span, a {
            line-height: 1.8rem;
        }
        & + p {
            margin-top: 0.4rem;
        }
    }
}
</style>

<div class="flex-box_wrap">
    <div class="img_char">
        <span><img src="https://i.imgur.com/tpr5jcv.png" /></span>
    </div>
    <ul class="_type__01">
        <li>
            <strong>Name</strong>
            <div class="list_text">
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/apple/354/technologist-light-skin-tone_1f9d1-1f3fb-200d-1f4bb.png" /></i>
                    <span>Hyunsoo Zo</span>
                </p>
            </div>
        </li>
        <li>
            <strong>Education</strong>
            <div class="list_text">
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/apple/354/student-light-skin-tone_1f9d1-1f3fb-200d-1f393.png" /></i>
                    <span>Bachelor's degree in International Trade</span>
                </p>
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/apple/354/tent_26fa.png" /></i>
                    <span>ZeroBase BootCamp(BackEnd course)</span>
                </p>
            </div>
        </li>
        <li>
            <strong>Speaks</strong>
            <div class="list_text">
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/apple/354/speaking-head_1f5e3-fe0f.png" /></i>
                    <span>Korean(Native) , English(Advanced)</span>
                </p>
            </div>
        </li>
        <li>
            <strong>Skills</strong>
            <div class="list_text">
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/toss-face/342/regional-indicator-symbol-letter-j_1f1ef.png" /></i>
                    <span>Java , Spring(Boot)</span>
                </p>
            </div>
        </li>
        <li>
            <strong>Interests</strong>
            <div class="list_text">
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/microsoft/319/globe-with-meridians_1f310.png" /></i>
                    <span>Web Application,Server</span>
                </p>
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/apple/354/high-voltage_26a1.png" /></i>
                    <span>Performance optimization</span>
                </p>
            </div>
        </li>
        <li>
            <strong>Contact</strong>
            <div class="list_text">
                <p>
                    <i><img src="https://github.com/fluidicon.png" /></i>
                    <a href="https://github.com/HyunsooZo">Github</a>
                </p>
                <p>
                    <i><img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" /></i>
                    <a href="https://www.linkedin.com/in/hyunsoo-jo-605554186/?locale=en_US">LinkedIn</a>
                </p>
                <p>
                    <i><img src="https://em-content.zobj.net/thumbs/240/twitter/348/envelope_2709-fe0f.png" /></i>
                    <a href="mailto:bzhs1992@icloud.com">bzhs1992@icloud.com</a>
                </p>
            </div>
        </li>
    </ul>
</div>