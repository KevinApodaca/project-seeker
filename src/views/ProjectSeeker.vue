<template>
  <div class="about">
    <div class="columns is-multiline">
      <div class="column is-8 is-offset-2 register">
        <div class="columns">
          <div class="column left">
            <h1 class="title is-1">Start Finding Projects!</h1>
            <h2 class="subtitle colored is-4">It's a really simple process</h2>
            <p class="message-body has-background-info-light">
              Please fill out this form with your key interests, as well as some
              of your most valuable skills. Click submit and we'll do the rest
              👍
            </p>
          </div>
          <div class="column right has-text-centered">
            <form class="box">
              <div class="field">
                <label class="label">Username</label>
                <div class="control has-icons-left has-icons-right">
                  <input
                    class="input"
                    type="text"
                    placeholder="your ldap"
                    value=""
                  />
                  <span class="icon is-small is-left">
                    <i class="fas fa-user"></i>
                  </span>
                </div>
              </div>
              <div class="field">
                <label class="label">Email</label>
                <div class="control has-icons-left has-icons-right">
                  <input
                    class="input"
                    type="email"
                    placeholder="email pls"
                    value=""
                  />
                  <span class="icon is-small is-left">
                    <i class="fas fa-envelope"></i>
                  </span>
                </div>
              </div>
              <p class="has-text-left has-text-small">I am interested in...</p>
              <div class="field has-addons">
                <div class="control is-expanded">
                  <div class="select is-fullwidth is-rounded is-info">
                    <select name="interest">
                      <option value="AI">Artificial Intelligence</option>
                      <option value="ML">Machine Learning</option>
                      <option value="INFRA">Infrastructure</option>
                      <option value="BD">Big Data</option>
                      <option value="NW">Networking</option>
                    </select>
                  </div>
                </div>
              </div>
              <p class="has-text-left has-text-small">and also</p>
              <div class="field has-addons">
                <div class="control is-expanded">
                  <div class="select is-fullwidth is-rounded is-info">
                    <select name="interest2">
                      <option value="BD">Big Data</option>
                      <option value="NW">Networking</option>
                      <option value="ML">Machine Learning</option>
                      <option value="AI">Artificial Intelligence</option>
                      <option value="INFRA">Infrastructure</option>
                    </select>
                  </div>
                </div>
              </div>
              <div class="field">
                <label class="label">Skill 1</label>
                <div class="control">
                  <div class="select">
                    <select>
                      <option value="">kubernetes</option>
                      <option>nodejs</option>
                      <option>python</option>
                      <option>terraform</option>
                      <option>ui/ux</option>
                    </select>
                  </div>
                </div>
              </div>
              <div class="field">
                <label class="label">Skill 2</label>
                <div class="control">
                  <div class="select">
                    <select>
                      <option>nodejs</option>
                      <option>kubernetes</option>
                      <option>terraform</option>
                      <option>ui/ux</option>
                      <option>python</option>
                    </select>
                  </div>
                </div>
              </div>
              <div class="field">
                <label class="label">Skill 3</label>
                <div class="control">
                  <div class="select">
                    <select>
                      <option>ui/ux</option>
                      <option>python</option>
                      <option>nodejs</option>
                      <option>terraform</option>
                      <option>kubernetes</option>
                    </select>
                  </div>
                </div>
              </div>
              <div class="field">
                <label class="label">Skill 4</label>
                <div class="control">
                  <div class="select">
                    <select>
                      <option>python</option>
                      <option>kubernetes</option>
                      <option>nodejs</option>
                      <option>ui/ux</option>
                      <option>terraform</option>
                    </select>
                  </div>
                </div>
              </div>

              <button class="button is-block is-primary is-fullwidth is-medium">
                Submit
              </button>
              <br />
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
